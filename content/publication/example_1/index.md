---
title: 'A Computationally Efficient Approach for Stochastic Reachability Set Analysis'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - D Gueho
  - P Singla

<!--# Author notes (optional)-->
<!--author_notes:-->
<!--  - 'Equal contribution'-->
<!--  - 'Equal contribution'-->

date: '2020-01-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 2020 AIAA SciTech Forum and Exposition, Orlando, FL


abstract: The reachability set is defined as the collection of all states which can be traversed from arbitrary initial conditions due to the application of admissible control. Three different prob- abilistic approaches to compute the reachability sets for a class of discrete time nonlinear systems is discussed. The main idea of the probabilistic approach is to consider the bounded control variables as random variables and represent the reachability sets as the level sets of the state probability density function. In the first approach, the computation of the state density function due to variation in control input at each time is made tractable by computing the M- fold convolution of state density function at each time. To overcome the significant challenge of taking multi-dimension convolution of state density function, the second approach computes the probability density function using the Principle of Maximum Entropy (PME). The third approach utilizes the Conjugate Unscented Transform (CUT) method to curtail the combina- torial growth of samples. Finally, three numerical example problems are considered to show the efficacy and utility of the proposed ideas.


tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'example_1'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Convolution Illustration'
  focal_point: ''
  preview_only: false

---
<!---->
<!--{{% callout note %}}-->
<!--Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.-->
<!--{{% /callout %}}-->

<!--{{% callout note %}}-->
<!--Create your slides in Markdown - click the _Slides_ button to check out the example.-->
<!--{{% /callout %}}-->
<!---->
<!--Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).-->
