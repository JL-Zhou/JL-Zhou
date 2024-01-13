---
title: 'Differential Privacy based on Bayesian Optimisation in Deep Neural Networks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Jiling Zhou

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-09-01'
# doi: ''

# # Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# # Publication type.
# # Accepts a single type but formatted as a YAML list (for Hugo requirements).
# # Enter a publication type from the CSL standard.
# publication_types: ['paper-conference']

# # Publication name and optional abbreviated publication name.
# publication: In *Hugo Blox Builder Conference*
# publication_short: In *ICW*

abstract: The objective of this project is to explore the integration of local differential privacy into deep neural networks (DNNs) through the utilisation of Bayesian optimisation. The pur- pose of this research is to achieve a trade-off between preserving privacy and maintaining the effectiveness of the model, with a specific focus on medical applications. By implementing a three- hidden-layer feed-forward neural network (FFNN) encompassing three levels (Normal, Prediabetes, and Diabetes), we have suc- cessfully classified a dataset related to diabetes for the intent of diagnosis. The Laplace mechanism is applied in conjunction with local differential privacy to enhance the privacy assurance of FFNN. This method provides an efficient way of safeguarding the privacy of data samples, while simultaneously attaining optimal model accuracy. Furthermore, we illustrate the benefits of using the Laplace mechanism in preserving privacy compared to the Gaussian mechanism. In addition, we confirm that the integration of differential privacy in DNNs is capable of producing precise predictions while upholding privacy. Additionally, the experiment demonstrates the efficacy of Bayesian optimisation in the context of multi-objective optimisation within privacy scenarios, while also identifying the most optimal hyper-parameter configurations. This approach provides evidence that the utilisation of Bayesian optimisation leads to enhanced accuracy in the FFNN model, as well as in the Laplace and Gaussian mechanisms (privacy). We put forward an argument regarding the limited influence of Bayes’s theorem on the K-anonymity mechanism. This work offers a comprehensive framework for enhancing the efficiency and structure of DNNs in order to classify medical data while ensuring enhanced privacy guarantees.


# Summary. An optional shortened abstract.
Index Terms: —Deep neural networks (DNNs), Differential privacy, Feed-forward neural network, Laplace mechanism, Bayesian optimisation
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '../publication/1masterthesis/final_report_v4.pdf'
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# # Featured image
# # To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# # Associated Projects (optional).
# #   Associate this publication with one or more of your projects.
# #   Simply enter your project's folder or file name without extension.
# #   E.g. `internal-project` references `content/project/internal-project/index.md`.
# #   Otherwise, set `projects: []`.
# projects:
#   - example

# # Slides (optional).
# #   Associate this publication with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides: "example"` references `content/slides/example/index.md`.
# #   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->

<!-- {{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
