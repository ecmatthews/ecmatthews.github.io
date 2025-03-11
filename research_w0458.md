[Home](index) &emsp; &emsp; [Research](research) &emsp; &emsp; [Outreach](outreach) &emsp; &emsp; [Media](media)
&emsp;

On this page you can find some plots and data associated with my paper [Matthews et al. 2025](https://ui.adsabs.harvard.edu/abs/2025arXiv250213610M/abstract), titled **HCN and C<sub>2<\sub>H<sub>2</sub> in the atmosphere of a T8.5+T9 brown dwarf binary**.

1. Interactive plot of the data and the best-fit model. Click [here](projects/model_vs_data.html) for a full-page version.

    <iframe style="position: relative; width: 100%; height:300px" frameborder="0" scrolling="no" src="https://ecmatthews.github.io/projects/model_vs_data.html"></iframe>

2. Interactive plot of the data, and several models with and without HCN/C<sub>2</sub>H<sub>2</sub> included. Click [here](projects/models_hcn_c2h2.html) for a full-page version.

    <iframe style="position: relative; width: 100%; height:300px" frameborder="0" scrolling="no" src="https://ecmatthews.github.io/projects/models_hcn_c2h2.html"></iframe>

3. Extracted 1D spectrum, as presented in Matthews et al. 2025. This includes the background systematics correction described in Appendix C of the paper, and treats the binary as an unresolved object. We provide a spectrum at the native resolution of the instrument (Rinst), and a spectrum degraded to R=1000, as used in the retrievals in Matthews et al. 2025 (see paper for details).

    [Data at Instrumental Resoluion](datafiles/w0458_modelspectrum_Rinst.txt)

    [Data at R=1000 (used for retrievals)](datafiles/w0458_modelspectrum_R1000.txt)


4. Best-fit model for W0458 as presented in Matthews et al. 2025, as retrieved with pRT ([Mollière et al. 2019](https://ui.adsabs.harvard.edu/abs/2019A%26A...627A..67M/abstract), [Nasedkin et al. 2024](https://ui.adsabs.harvard.edu/abs/2024JOSS....9.5875N/abstract)). This model has 21 free parameters, namely: the planet radius, the planet logg, a P-T profile defined by 10 temperature nodes equally spaced between 10<sup>3</sup>bar and 10<sup>-5</sup>bar and a gamma-parameter, seven molecular species (H<sub>2</sub>O, CH<sub>4</sub>, NH<sub>3</sub>, HCN, C<sub>2</sub>H<sub>2</sub>, CO and CO<sub>2</sub>), and a b-parameter to allow for uncertainty inflation. The modelling is described in detail in Matthews et al. 2025, and best-fit parameters can be found in Table 1 of the paper.

    [Best-fit model spectrum derived with pRT](datafiles/w0458_modelspectrum_pRT.txt)