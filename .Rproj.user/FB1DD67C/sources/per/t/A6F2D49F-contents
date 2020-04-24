library(shiny)


ui <- fluidPage(
  tags$head(
    tags$script(src = "fullpage.js"),
    includeCSS("www/fullpage.css"),
    includeCSS("www/style.css")
  ),
  tags$div(id = "fullpage",
    tags$div(class = "section",
      tags$div(class = "slide active",
         tags$div(class = "heading", id = "cover",
                  tags$h1("Pink Anarchy")
                  ),
         tags$div(class = "author", 
                  tags$h4("Jose Figueroa"))
               ),
      tags$div(class = "slide", id = "p1",
         tags$div(class = "p1meme",
         tags$img(src="img/anarchymeme.png")
         )
         ),
      tags$div(class = "slide page", id = "p2",
         tags$div(class = "p2bg",
         tags$img(src="img/marshasis.jpg")
         ),
         tags$div(class = "p2body",
         tags$h3(
            "The trans people of color are the ones who started the stonewall rebellion. 
            Marsha P. Johnson and Sylvia Rivera, you wanna know what they faced? Paying
            your dues with hair, teeth, skin and bones. - Rennée Imperato"
         )
         )
         ),
        tags$div(class = "slide page", id = "p3",
           tags$div(class = "question",
           tags$h2("Can queer liberation exist in a capitalist society?")
           ),
           tags$span(class = "p3imgtop",
             tags$img(src="img/Queer_Liberation_Not_Rainbow_Capitalism.jpg", style="height:45%;")),
           hr(),
           tags$span(class = "p3imgbtm",
             tags$img(src="img/no_pride_in_yt.jpg",  style="height:50%;"))
      ),
      tags$div(class = "slide page", id = "p4",
          tags$div(class = "p4body",
          tags$h3(
            "At its heart, capitalism is a system that seeks to exploit people for labor. 
            Oppression is the feature, not the bug. It is my belief that true queer 
            liberation cannot exist in a system that exists to exploit others, that 
            exists only to enable hierarchies and ‘others’. I say this not to be pessimistic, 
            but to expand our imaginations to what true freedom from oppression can look like. 
            I don’t want to be free if it is solely in the context of an oppressive system."
          )
          )
      ),
      tags$div(class = "slide", id = "p5",
               tags$div(class = "p5wrapper1",
               tags$div(class = "p5logo",
                        tags$img(src="img/asimnotlib.jpg", style="width:100%; float:left; margin-top: 10px;")
               ),
               tags$div(class = "p5logotext",
                 tags$h4("Desde mi punto de vista el capital, el capitalismo, lo que hace es 
                 simplificar. Como modelo de producción, como modelo de producción de 
                 bienes y de vida. Pero no sólo produce bienes consumibles, sino produce 
                 vidas. Primero simplifica, tiene otras muchas visiones es desmovilizar. 
                 No le interesa movimientos diversos. Y generar productos homogeneizados - 
                 es decir que sean iguales, y se pueden intercambiar. Y despolitizados. 
                 Esas son señas principales de lo que llamamos sistema capitalista global 
                 actual. Desmovilizar, generar productos homogeneizados, y despolitizar. - Fefa Vila"))),
               hr(),
               tags$div(class = "p5wrapper2",
               tags$div(class = "p5gaymartext",
                tags$img(src="img/gaymarriage.png", style = "width:100%; padding-bottom: 5%;"),
                "The latest war-cry of the HRC concerns the unfairness of the fact that “more 
                than 1,100 federal benefits and protections of marriage” are extended to 
                straight couples but not to gay couples. This complaint ignores the fact that 
                everyone deserves those rights. It ignores the fundamental unfairness and 
                inequality of the way marriage is privileged in the U.S. over all other 
                lifestyle choices (including singledom, queer unions of various levels of 
                exclusivity, and various informal arrangements not sanctioned by the state, 
                many of which are most common in communities of color).",
                tags$br(),
                "Queers have an opportunity to champion fundamentally new lifestyle 
                possibilities that could set new standards of fairness and equality. 
                These queer lifestyles could avoid and challenge the deep-rooted problems 
                of institutions like marriage. Some queers, in groups or as individuals, 
                do fight for these radical ways of living. Yet every single one of the major
                gay rights organizations advocates for our assimilation into preexisting 
                institutions rife with problems that they ignore and accept.- Solomon Grundy"
                        ),
               tags$div(class = "p5flag",
                 tags$img(src = "img/anarchogay.png", style = "width: 100%")
               ))
      ),
      tags$div(class = "slide page", id = "p6",
          tags$span(class = "p6heading",
          tags$h2(class = "rainbow-text",
          "Pink Capitalism"
          )
          ),
          tags$div(class = "p6meme",
          tags$img(src="img/rosapigs.jpg", style = "width: 50%;"),
          tags$img(src="img/gaycap.jpg", style = "width: 50%")
          )
      )
      
     )
  ),
  tags$script(
    HTML(
      "var myFullpage = new fullpage('#fullpage', {
        lazyLoad: true
    });"
    )
  )
)

server <- function(input, output, session) {
  
}

shinyApp(ui = ui, server = server)