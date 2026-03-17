\subsubsection{Appearance of the Six Parameters in the Temperature Power Spectrum}

The angular power spectrum of the CMB temperature anisotropies may be expressed as
\begin{equation}
  C_\ell^{TT}
  =
  4\pi \int d\ln k \,
  \Delta_\zeta^2(k)\,
  \left|
    \frac{\Theta_\ell(k,\eta_0)}{\zeta(k)}
  \right|^2 ,
  \label{eq:ClTT_LCDM6}
\end{equation}
where \(\Theta_\ell(k,\eta_0)\) is the photon transfer function evaluated today,
obtained from the Einstein--Boltzmann equations, and \(\Delta_\zeta^2(k)\)
is the dimensionless primordial curvature power spectrum. This expression
is useful because it separates the primordial initial conditions from the
late-time linear evolution encoded in the transfer function.

The primordial parameters \(A_s\) and \(n_s\) appear through
\(\Delta_\zeta^2(k)\), while the remaining four parameters
\(\Omega_b h^2\), \(\Omega_c h^2\), \(\theta_\ast\), and \(\tau\)
enter through \(\Theta_\ell(k,\eta_0)\). Physically, these parameters determine
the background expansion, the sound speed in the photon--baryon fluid, the
time of matter--radiation equality, the angular diameter distance to the
surface of last scattering, and the effect of reionization on the observed anisotropies.

Their principal effects on the temperature spectrum may be summarized as follows:
\begin{itemize}
  \item \(\Omega_b h^2\): determines the baryon loading of the photon--baryon fluid,
        thereby enhancing compressional peaks relative to rarefaction peaks and
        modifying the odd/even peak-height ratio;
  \item \(\Omega_c h^2\): determines the redshift of matter--radiation equality and
        hence affects the early integrated Sachs--Wolfe contribution and the
        gravitational driving of the acoustic oscillations;
  \item \(\theta_\ast\): sets the observed angular size of the sound horizon at
        recombination and therefore fixes the peak locations in multipole space;
  \item \(\tau\): suppresses the primary temperature anisotropies on small angular
        scales by approximately \(e^{-2\tau}\) because rescattering during reionization
        reduces the contrast of the anisotropies formed at last scattering;
  \item \(A_s\): fixes the overall amplitude of the primordial scalar fluctuations
        and hence the overall normalization of the spectrum;
  \item \(n_s\): controls the tilt of the primordial spectrum and therefore changes
        the relative amount of power on large and small scales.
\end{itemize}

Within minimal \(\Lambda\)CDM, these six parameters are sufficient to describe
the primary CMB temperature anisotropy spectrum to high precision. In practice,
their values are inferred by comparing the theoretical prediction in
Eq.~\eqref{eq:ClTT_LCDM6} with the observed bandpowers from experiments such as
\textit{Planck} and ACT.
