# Analysing multivariate ecological data with Generalized Linear Latent Variable Models
Thanks for participating, and welcome to this  workshop on the <tt>gllvm</tt> R-package.

## Installation instructions

Before continuing further to the exercise material, please make sure you have installed the following, required, R-packages:
```r
install.packages("corrplot")
install.packages("dplyr")
install.packages("mvabund")
install.packages("gllvm")
```

If you are on a linux operating system, make sure that gsl is installed (outside of R). If, during installation of the <tt>gllvm</tt> R-package you are getting an error relating to the R-package <tt>RccpGSL</tt>, go to the linux command line an run <tt>sudo apt install libgsl-dev</tt>.

If you encounter any other problems while installing any of the packages above (especially <tt>mvabund</tt> or <tt>gllvm</tt>, and you are using an old(er) R version, please try to update R. If after doing so you still encounter issues with the installation, please contact us.

If you encounter any problems when using the <tt>gllvm</tt> R-package, please explore [existing issues in the github repository of the package](https://github.com/JenniNiku/gllvm/issues). If your problem has not already been posted by someone else, feel free to post a new issue or use the [discussion board](https://github.com/BertvanderVeen/BES2020GLLVMworkshop/discussions) in this repository.

# Workshop material
All workshop material can be found in this repository, listed below. If you would like to download all material at once, click the bright green button above (and select the bottom option: download zip). Material from our workshop at the Festival of Ecology is availalbe here: https://github.com/BertvanderVeen/BES2020GLLVMworkshop with recordings: https://t.co/eWfbfk27Fu?amp=1.

Further example material on using the <tt>gllvm</tt> R-package is available in the vignettes, and the [reference manual](https://cran.r-project.org/web/packages/gllvm/gllvm.pdf), of the package:<br>
https://jenniniku.github.io/gllvm/articles/ <br>
https://jenniniku.github.io/gllvm/articles/vignette1.html <br>
https://jenniniku.github.io/gllvm/articles/vignette2.html <br>
https://jenniniku.github.io/gllvm/articles/vignette3.html <br>
https://jenniniku.github.io/gllvm/articles/vignette4.html <br>
https://jenniniku.github.io/gllvm/articles/vignette5.html <br>
https://jenniniku.github.io/gllvm/articles/vignette6.html <br>

# Questions
Any questions regarding the exercise material can be posted on the discussion board, or communicated over twitter using the [#GLLVMs hashtag](https://twitter.com/search?q=GLLVMs&src=typed_query&f=live), directed [@vdVeenB](https://twitter.com/vdVeenB), [@J__Niku](https://twitter.com/J__Niku), or [@samperrinNTNU](https://twitter.com/samperrinNTNU).

Alternatively, you can contact us by e-mail: bert.vanderveen@nibio.no, jenni.m.e.niku@jyu.fi, or sam.perrin@ntnu.no.

# Some recommended reading
[Blanchet, F., Cazelles, K., & Gravel, D. (2020). Co-occurrence is not evidence of ecological interactions. Ecology Letters, 23(7), 1050 - 1063.](https://onlinelibrary.wiley.com/doi/abs/10.1111/ele.13525)

[Clark, J., Gelfand, A., Woodall, C., & Zhu, K. (2014). More than the sum of the parts: forest climate response from joint species distribution models. Ecological Applications, 24(5), 990 - 999.](https://esajournals.onlinelibrary.wiley.com/doi/abs/10.1890/13-1015.1)

[D'Amen, M., Mod, H., Gotelli, N., & Guisan, A. (2018). Disentangling biotic interactions, environmental filters, and dispersal limitation as drivers of species co-occurrence. Ecography, 41(8), 1233 - 1244.](https://onlinelibrary.wiley.com/doi/full/10.1111/ecog.03148)

[Halvorsen, R. (2012). A gradient analytic perspective on distribution modelling. Sommerfeltia, 35(1), 1 - 165.](http://nhm2.uio.no/botanisk/nbf/temp/Sommerfeltia_35_20121206_PRESS.pdf)

[Hui, F.K.C., Taskinen, S., Pledger, S., Foster, S., & Warton, D. (2015). Model-based approaches to unconstrained ordination. Methods in Ecology and Evolution, 6(4), 399 - 411.](https://besjournals.onlinelibrary.wiley.com/doi/10.1111/2041-210X.12236)

[Hui, F.K.C., Warton, D., Ormerod, J., Haapaniemi, V., & Taskinen, S. (2017). Variational approximations for generalized linear latent variable models. Journal of Computational and Graphical Statistics, 26(1), 35 - 43.](https://www.tandfonline.com/doi/abs/10.1080/10618600.2016.1164708)

[Niku, J., Warton, D., Hui, F.K.C., & Taskinen, S. (2017). Generalized linear latent variable models for multivariate count and biomass data in ecology. Journal of Agricultural, Biological and Environmental Statistics, 22(4), 498 - 522.](https://link.springer.com/article/10.1007/s13253-017-0304-7)

[Niku, J., Hui, F.K.C., Taskinen, S., & Warton, D. (2019). gllvm: Fast analysis of multivariate abundance data with generalized linear latent variable models in r. Methods in Ecology and Evolution, 10(12), 2173 - 2182.](https://besjournals.onlinelibrary.wiley.com/doi/abs/10.1111/2041-210X.13303)

[Niku, J., Brooks, W., Herliansyah, R., Hui, F.K.C., Taskinen, S., & Warton, D. (2019). Efficient estimation of generalized linear latent variable models. PloS one, 14(5), e0216129.](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0216129)

[Ovaskainen, O., Tikhonov, G., Norberg, A., F.G. Blanchet, Duan, L., Dunson, D., Roslin, T. & Abrego, N. (2017). How to make more out of community data? A conceptual framework and its implementation as models and software. Ecology Letters, 20(5), 561 - 576.](https://onlinelibrary.wiley.com/doi/10.1111/ele.12757)

[Poggiato, G.,  MÃ¼nkemÃ¼ller, T., Bystrova, D., Arbel, J., Clark, J.S. & Thuiller, W. (2021). On the interpretations of joint omdeling in community ecology. Trends in Ecology and Evolution, 36(5), 391 -  401.](https://doi.org/10.1016/j.tree.2021.01.002)

[Pollock, L., Tingley, R., Morris, W., Golding, N., O'Hara, R., Parris, K., Vesk, P., & McCarthy, M. (2014). Understanding co-occurrence by modelling species simultaneously with a Joint Species Distribution Model (JSDM). Methods in Ecology and Evolution, 5(5), 397 - 406.](https://besjournals.onlinelibrary.wiley.com/doi/10.1111/2041-210X.12180)

[van der Veen, B., Hui, F.K.C., Hovstad, K.A., Solbu, E.B., & O'Hara, R.B. (2021). Model-based ordination for species with unequal niche widths. Methods in Ecology and Evolution, 12(7), 1288 - 1300.](https://besjournals.onlinelibrary.wiley.com/doi/abs/10.1111/2041-210X.13595)

[Wang, Y., Naumann, U., Wright, S., & Warton, D. (2012). mvabund an R package for model-based analysis of multivariate abundance data. Methods in Ecology and Evolution, 3(3), 471 - 474.](https://besjournals.onlinelibrary.wiley.com/doi/10.1111/j.2041-210X.2012.00190.x)

[Warton, D., Wright, S., & Wang, Y. (2012). Distance-based multivariate analyses confound location and dispersion effects. Methods in Ecology and Evolution, 3(1), 89 - 101.](https://besjournals.onlinelibrary.wiley.com/doi/abs/10.1111/j.2041-210X.2011.00127.x)

[Warton, D., Blanchet, F., O'Hara, R., Ovaskainen, O., Taskinen, S., Walker, S., & Hui, F.K.C. (2015). So many variables: joint modeling in community ecology. Trends in Ecology & Evolution, 30(12), 766 - 779.](https://doi.org/10.1016/j.tree.2015.09.007)

[Warton, D., Foster, S., Deâath, G., Stoklosa, J., & Dunstan, P. (2015). Model-based thinking for community ecology. Plant Ecology, 216(5), 669 - 682.](https://link.springer.com/article/10.1007/s11258-014-0366-3)

[Warton, D., & Hui, F.K.C. (2017). The central role of mean-variance relationships in the analysis of multivariate abundance data: a response to Roberts (2017). Methods in Ecology and Evolution, 8(11), 1408 - 1414.](https://besjournals.onlinelibrary.wiley.com/doi/abs/10.1111/2041-210X.12843)

[Zurell, D., Zimmermann, N., Gross, H., Baltensweiler, A., Sattler, T., & WÃ¼est, R. (2020). Testing species assemblage predictions from stacked and joint species distribution models. Journal of Biogeography, 47(1), 101 - 113.](https://onlinelibrary.wiley.com/doi/abs/10.1111/jbi.13608)

