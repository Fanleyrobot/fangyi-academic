+++
title = "Adversarial Discriminative Sim-to-real Transfer of Visuo-motor Policies"
date = 2018-05-31T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Fangyi Zhang**", "Jürgen Leitner", "Zongyuan Ge", "Michael Milford", "Peter Corke"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["3"]

# Publication name and optional abbreviated version.
publication = "In *The International Journal of Robotics Research (IJRR)* (**Under Review**)."
publication_short = "In *IJRR* (**Under Review**)"

# Abstract and optional shortened version.
abstract = "Various approaches have been proposed to learn visuo-motor policies for real-world robotic applications. One solution is first learning in simulation then transferring to the real world. In the transfer, most existing approaches need real-world images with labels. However, the labelling process is often expensive or even impractical in many robotic applications. In this paper, we propose an adversarial discriminative sim-to-real transfer approach to reduce the cost of labelling real data. The effectiveness of the approach is demonstrated with modular networks in a table-top object reaching task where a 7 DoF arm is controlled in velocity mode to reach a blue cuboid in clutter through visual observations. The adversarial transfer approach reduced the labelled real data requirement by 50%. Policies can be transferred to real environments with only 93 labelled and 186 unlabelled real images. The transferred visuo-motor policies are robust to novel (not seen in training) objects in clutter and even a moving target, achieving a 97.8% success rate and 1.8 cm control accuracy."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename of your project in `content/project/`.
#   Otherwise, set `projects = []`.
projects = []

# Links (optional).
url_pdf = ""
url_preprint = "https://arxiv.org/abs/1709.05746.pdf"
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = "https://youtu.be/bVIw1DeuuYg"
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

# image = "headers/bubbles-wide.jpg"
# caption = "My caption :smile:"

+++

{{< youtube bVIw1DeuuYg >}}

<!-- More detail can easily be written here using *Markdown* and $\rm \LaTeX$ math code. -->
