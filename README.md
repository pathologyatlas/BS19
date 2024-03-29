





```
r language BS19, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis psödoinklüzyon, ilaç etkisi, karaciğer, KİT hastası TR, echo = (language == "TR")
## BS19 - psödoinklüzyon, ilaç etkisi, karaciğer, KİT hastası {#sec-BS19 }
```


```
asis pseudoinclusion, drug-induced injury, liver, bone marrow transplantation history EN, echo = (language == "EN")
## BS19 - pseudoinclusion, drug-induced injury, liver, bone marrow transplantation history {#sec-BS19 }
```






```
r BS19 screenshot HE, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/BS19-HE_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/BS19/HE.html",
  file = "./screenshots/BS19-HE_screenshot.png"
)
}
```





::::: panel-tabset


### WSI - Link










[https://images.patolojiatlasi.com/BS19/HE.html](https://images.patolojiatlasi.com/BS19/HE.html)





```
asis, echo = (language == "TR")

**psödoinklüzyon, ilaç etkisi, karaciğer, KİT hastası**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/BS19-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS19/HE.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/BS19/HE.html)
```

```
asis, echo = (language == "EN")

**pseudoinclusion, drug-induced injury, liver, bone marrow transplantation history**

[![Click for Full Screen WSI](./screenshots/BS19-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS19/HE.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/BS19/HE.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/BS19/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/BS19/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





### Diagnosis


```
asis, echo = (language == "TR")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Tanı için tıklayın

psödoinklüzyon, ilaç etkisi, karaciğer, KİT hastası

:::


```


```
asis, echo = (language == "EN")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Click for Diagnosis

pseudoinclusion, drug-induced injury, liver, bone marrow transplantation history

:::

```









:::::








