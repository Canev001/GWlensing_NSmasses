# Impact of lensing of gravitational waves on the observed distribution of neutron star masses

Mock catalogues of events used in https://arxiv.org/abs/2404.11480. 

For each mass distribution, 10 independent realisations of $10^5$ events are avalilable, except for the Gaussian case with $m_{\rm max}=2.5 M_{\odot}$ for which we consider 20 realisations. Each realisation is obtained by independently drawing values for the redshifts  $z$, masses $(m_1,m_2)$, angles $(\psi,\iota, \theta)$ and lensing magnifications $\mu$. 

The data files contain columns of $\bigg(\frac{d_L}{\sqrt{\mu}}[\rm m], \rho, z, \mu, (1+z)m_1 [M_{\odot}], (1+z)m_2 [M_{\odot}], \psi, \iota, \theta\bigg)$.

The mock data are relevant for gravitational waves emitted by merging binary neutron stars measured by the **Einstein Telescope**, 
assuming a threshold for the signal-to-noise ratio of **8**.

## Credit

If you use the data, please cite:

  ```sh
 @article{Canevarolo:2024muf,
    author = "Canevarolo, Sofia and van Vonderen, Loek and Chisari, Nora Elisa",
    title = "{Impact of lensing of gravitational waves on the observed distribution of neutron star masses}",
    eprint = "2404.11480",
    archivePrefix = "arXiv",
    primaryClass = "astro-ph.CO",
    month = "4",
    year = "2024"
}
