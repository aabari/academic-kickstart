+++
title = "A Simple PTAS for the Dual Bin Packing Problem and Advice Complexity of Its Online Version"
date = "2017-10-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Allan Borodin", "Denis Pankratov", "Amirali Salehi-Abari"]


# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In *Proceedings of the The 1st Symposium on Simplicity in Algorithms  (SOSA'17)*."
publication_short = "In *SOSA*"



# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

abstract = "Recently, Renault (2016) studied the dual bin packing problem in the per-request advice model of online algorithms. He showed that given $O(1/ \\epsilon)$ advice bits for each input item allows approximating the dual bin packing problem online to within a factor of $1+ \\epsilon$. Renault asked about the advice complexity of dual bin packing in the tape-advice model of online algorithms. We make progress on this question. Let $s$ be the maximum bit size of an input item weight. We present a conceptually simple online algorithm that with total advice $O\\left(\\frac{s + \\log n}{\\epsilon^2}\\right)$ approximates the dual bin packing to within a $1+\\epsilon$ factor. To this end, we describe and analyze a simple offline PTAS for the dual bin packing problem. Although a PTAS for a more general problem was known prior to our work (Kellerer 1999, Chekuri and Khanna 2006), our PTAS is arguably simpler to state and analyze. As a result, we could easily adapt our PTAS to obtain the advice-complexity result. We also consider whether the dependence on $s$ is necessary in our algorithm. We show that if $s$ is unrestricted then for small enough $\\epsilon > 0$ obtaining a $1+\\epsilon$ approximation to the dual bin packing requires $\\Omega_\\epsilon(n)$ bits of advice. To establish this lower bound we analyze an online reduction that preserves the advice complexity and approximation ratio from the binary separation problem due to Boyar et al. (2016). We define two natural advice complexity classes that capture the distinction similar to the Turing machine world distinction between pseudo polynomial time algorithms and polynomial time algorithms. Our results on the dual bin packing problem imply the separation of the two classes in the advice complexity world."

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = ["Online-Algorithms"]

# Links (optional).
url_pdf = "files/pdfs/PTAS-SOSA18.pdf"
#url_preprint = ""
#url_code = "#"
#url_dataset = "#"
#url_project = "#"
#url_slides = "#"
#url_video = "#"
#url_poster = "#"
#url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{name = "arXiv", url = "https://arxiv.org/abs/1708.01657"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
#[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++
