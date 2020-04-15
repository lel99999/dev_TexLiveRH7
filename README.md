# dev_TexLiveRH7
TexLive (LaTex) Notes on RHEL 7.x

## TexLive 2013
Add yum packages to address LaTeX error File 'framed.sty' not found.<br/>
`$sudo yum install texlive-framed`<br/>

## TexLive 2020
`$wget http://mirror.ctan.org/systems/texlive/tlnet/install-tl-unx.tar.gz`<br/>
`$tar -xvf install-tl-unx.tar.gz`<br/>
`$cd ./install-tl-20200415`<br/>
`$./install-tl -gui text`<br/>

*Change schema to schema-basic instead of schema-full*<br/>
