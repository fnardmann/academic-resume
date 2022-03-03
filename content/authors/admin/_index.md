---
# Display name
title: Felix Nardmann

# Is this the primary user of the site?
superuser: true

# Role/position/tagline
role: Software Engineer - LiDAR

# Organizations/Affiliations to show in About widget
organizations:
- name: SPIE Cegit
  url: https://spie.de/cegit

# Short bio (displayed in user profile at end of posts)
bio: My research interests include automatic point cloud analysis, deep learning and data processing.

# Interests to show in About widget
interests:
- LiDAR
- Artificial Intelligence
- Object Detection

# Education to show in About widget
education:
  courses:
  - course: M.Sc. Geoinformatics
    institution: University of Osnabrueck
    year: 2021
  - course: B.Sc. Geoinformatics
    institution: University of Osnabrueck
    year: 2019

# Social/Academic Networking
# For available icons, see: https://wowchemy.com/docs/getting-started/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "/#contact" for contact widget.
social:
- icon: envelope
  icon_pack: fas
  link: 'mailto:felix.nardmann@gmx.de'
# - icon: twitter
#   icon_pack: fab
#   link: https://twitter.com/GeorgeCushen
# - icon: graduation-cap  # Alternatively, use `google-scholar` icon from `ai` icon pack
#   icon_pack: fas
#   link: https://scholar.google.co.uk/citations?user=sIwtMXoAAAAJ
- icon: github
  icon_pack: fab
  link: https://github.com/fnardmann
- icon: linkedin
  icon_pack: fab
  link: https://www.linkedin.com/in/felix-nardmann-5a839a212/

# Link to a PDF of your resume/CV.
# To use: copy your resume to `static/uploads/resume.pdf`, enable `ai` icons in `params.toml`, 
# and uncomment the lines below.
# - icon: cv
#   icon_pack: ai
#   link: uploads/resume.pdf

# Enter email to display Gravatar (if Gravatar enabled in Config)
email: ""

# Highlight the author in author lists? (true/false)
highlight_name: true
---

Felix Nardmann is a software developer at SPIE Cegit working with LiDAR and deep learning. In 2021 he automatically classified power lines using Airborne LiDAR data and Deep Learning. In doing so, a framework was built using Python and Tensorflow that can use the standard [PointNet](https://github.com/charlesq34/pointnet) method as well as more advanced approaches such as [Pointnet++](https://github.com/charlesq34/pointnet2), [PointSIFT](https://github.com/MVIG-SJTU/pointSIFT), [PointConv](https://github.com/DylanWusee/pointconv), [GACNET](https://github.com/wleigithub/GACNet) or [DGCNN](https://github.com/WangYueFt/dgcnn) to classify airborne LiDAR data. For a final prediction on an unknown test data set, accuracies of over $98\,\%$ and $96\,\%$ could be achieved for power lines and poles, respectively.

Especially in the course of his master studies he increasingly worked with machine learning methods like Random Forest or SVM. In the context of remote sensing, the main focus was on pixel- or object-based classification of satellite images using these methods. In this context, dimensionality reduction methods such as PCA were also applied. 

{{< icon name="download" pack="fas" >}} Download my resumé in {{< staticref "uploads/demo_resume.pdf" "newtab" >}}English{{< /staticref >}} or {{< staticref "uploads/demo_resume.pdf" "newtab" >}}German{{< /staticref >}}.
