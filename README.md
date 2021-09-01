# CTAB-GAN
This git is built for paper [CTAB-GAN: Effective Table Data Synthesizing](https://arxiv.org/pdf/2102.08369.pdf). As the paper is still under review, we try to not release the code for now. But since we received many emails from researchers regarding to the paper, we have following clarifications for them:
- For `mixed-type-encoder`, in the part the usage for non-numeric category, we originally mentioned `We can map these symbols to a numeric value outside of the rangeof the continuous region.`. But actually according to our newest test, as encoding of beta is already indicating the category. Therefore, for all the category in mixed data type column (no matter numeric or non-numeric), we recommand to encode them alpha as 0. 
- If researchers want to impmlement the code before the releasing from us, we recommand to check the code of [CTGAN](https://github.com/sdv-dev/CTGAN) first. 

We will keep updating this github.

Currently, to cite this paper, you could use this bibtex
```
@article{zhao2021ctab,
  title={CTAB-GAN: Effective Table Data Synthesizing},
  author={Zhao, Zilong and Kunar, Aditya and Van der Scheer, Hiek and Birke, Robert and Chen, Lydia Y},
  journal={arXiv preprint arXiv:2102.08369},
  year={2021}
}
```
