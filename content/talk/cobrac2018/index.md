+++
title = "COBRAC 2018"
date = 2018-11-01T00:00:00  # Schedule page publish date.
draft = false

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
time_start = 2018-10-23T11:00:00
time_end = 2018-10-23T12:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Luiz F. P. Droubi", "Willian Zonato", "Norberto Hochheim"]

# Abstract and optional shortened version.
abstract = "Um procedimento muito comum na área de engenharia de avaliações é a adoção de transformações das variáveis para a obtenção de um modelo de regressão “melhor” ajustado. Dentre tais transformações, a mais usual e preferida de muitos avaliadores é a função logaritmo, especialmente para a variável dependente. Muitas vezes esta transformação é adequada e percebe-se uma notória melhora no ajuste do modelo. Outras vezes, esta transformação pode não ser adequada. Apesar do modelo aparentar-se melhor ajustado, problemas podem ocorrer quanto às verificações das hipóteses clássicas da regressão, as quais nem sempre os avaliadores estão tão atentos quanto estão com as verificações dos intervalos de confiança e níveis de significância. No entanto, o avaliador que assim procede estará verificando intervalos de confiança e níveis de significâncias incorretos, haja vista que a hipótese da heteroscedasticidade implica na incorreção destas inferências. Pretende-se apresentar aos avaliadores a importância da adoção de escolhas criteriosas para as transformações da variáveis através da análise do histograma da variável original e da variável transformada. Normalmente, uma boa escolha de transformação leva a uma distribuição aproximadamente normal. Quando a variável dependente apresenta distribuição lognormal, esta transformação é a transformação logarítmica. Desta maneira, descrevemos as características básicas desta distribuição, sua formulação, características além do seu relacionamento com a distribuição normal. Por fim, o presente estudo evindencia as implicações da adoção da transformação da variável dependente e o problema da retransformação da variável dependente à sua escala original."
abstract_short = "Apresentação na modalidade poster, no COBRAC 2018."

# Name of event and optional event URL.
event = "COBRAC 2018"
event_url = "http://cobrac2018.ufsc.br/"

# Location of event.
location = "Florianópolis, SC"

# Is this a selected talk? (true/false)
selected = false

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["internal-project"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://github.com/lfpdroubi/cobrac2018/raw/master/poster_dist_lognormal.pdf"
url_slides = "../../slides/dist_lognormal.html"
url_video = ""
url_code = ""

# Does the content use math formatting?
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  # caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++

{{% alert note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /alert %}}

Slides can be added in a few ways:

- **Create** slides using Academic's *Slides* feature and link using `url_slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://sourcethemes.com/academic/docs/writing-markdown-latex/).

Further talk details can easily be added to this page using *Markdown* and $\rm \LaTeX$ math code.
