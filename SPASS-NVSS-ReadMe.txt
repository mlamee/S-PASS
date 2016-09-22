Polarization Properties of Extragalactic Radio Sources   (Lamee+, 2016)
================================================================================================
MAGNETIC FIELD DISORDER AND FARADAY EFFECTS ON THE POLARIZATION OF EXTRAGALACTIC RADIO SOURCES
================================================================================================
ADC Keywords: Depolarization, Polarization, S-PASS, Extragalactic Radio sources, S band 
Keywords: Compact extragalactic Radio objects: Polarization, depolarization, Magnetic field, Faraday screen, Rotation measure

Abstract:
	We present a polarization catalog of 533 extragalactic radio sources with 2.3 GHz total intensity greater than 420 mJy from
	the S-band Polarization All Sky Survey, S-PASS, with corresponding polarization information at
	1.4 GHz from the NRAO VLA Sky Survey, NVSS. We carefully studied selection effects that might
	affect the compiled catalog. We found that the fractional polarization of radio objects depends
	on the spectral index, the source magnetic field disorder, source size and the depolarization. 
	The relationship between depolarization and the spectrum and the source size shows that this depolarization
	occurs primarily in a medium in the vicinity of the source. The median fractional polarization at 2.3 GHz of resolved objects
	in the NVSS beam is approximately two times larger than that of unresolved sources. Also, sources
	with depolarization D ∼1 are ∼2 times more polarized than both depolarized (D > 1) and re-polarized (D < 1) sources. 
	This indicates that intrinsic magnetic field disorder of the sources is the dominant mechanism responsible for the observed 
	low fractional polarization of radio sources at high frequencies. 
	We predict that number counts from polarization surveys at 1.4 GHz and at 2.3 GHz such as the VLASS will be similar at fixed sensitivity, 
	although we also see evidence that ∼10% of all sources may be depolarized heavily enough to be missing from our sample. 
	Objects with fractional polarization greater than 4% typically have simple Faraday structures, so can be used to make clean samples of background sources. 
	Almost half of the flat-spectrum (Alpha ≥ −0.5) and approximately 25% of steep-spectrum objects are re-polarized. 
	Steep spectrum, depolarized sources show weak signs of a negative correlation of their depolarization with redshift in the range 0 < z < 2.3. 
	Previous non-detections of redshift evolution are most likely due to source samples containing both re-polarized and depolarized sources.

Description:
	Radio 1.4 GHz and 2.3 GHz photometric and polarization catalog of 533 extragalctic objects above the Galactic plane, using the NVSS and S-PASS surveys.
	Additional information is presented from cross-matching the 533 sources with the Taylor et al. (2009) rotation measure catalog, the Hammond et al. (2012) redshift catalog 
	and the WISE catalog (Wright et al. 2010).  There has been significant processing of both the NVSS and S-PASS images, as described in the text.

File Summary:
--------------------------------------------------------------------------------
 FileName        Lrecl    Records    Explanations
--------------------------------------------------------------------------------
ReadMe           221          .      This file
SPASS—NVSS-V2.csv   555        533      Total intensity and polarization information of 533 extragalactic sources at 1.4 GHz and 2.3 GHz. Extra information such as redshift or WISE magnitudes are also collected if available.
--------------------------------------------------------------------------------

Byte-by-byte Description of file: SPASS-NVSS-V2.csv
--------------------------------------------------------------------------------
Bytes    Format  Units      Label           Explanation
--------------------------------------------------------------------------------
1-14     A14     ---        Tag             NVSS name tag (1)
16-27    F10.5   deg        RA              NVSS RA J2000 (1) 
29-40    F10.5   deg        DEC             NVSS DEC J2000 (1)
42-53    F10.5   deg        l               Galactic longtitude (1)
55-66    F10.5   deg        b               Galactic latitude (1)
68-77    F8.2    mJy        I_NV            NVSS target total intensity (I) + the contribution from contaminating objects 
79-88    F8.2    mJy        I_NV_err        NVSS I+contamination uncertainty 
90-99    F8.2    mJy        P_NV            NVSS target polarized intensity (P) + the contribution from contaminating objects   
101-110  F8.2    mJy        P_NV_err        NVSS P+contamination uncertainty 
112-121  F8.4    ---        Pi_NV           NVSS fractional polarization, In case of no detection the upper limit value is used.
123-132  F8.4    ---        Pi_Nv_err       NVSS fractional polarization uncertainty
134-142  I2      ---        Pi_NV_lim       NVSS fractional polarization upper limit flag,  limit=-1, detection=1
144-155  F10.4   deg        NV_pol_ang      NVSS polarization angle (1)
157-168  F10.4   deg        NV_pol_ang_err  NVSS polarization angle uncertainty (1)
170-179  F8.2    arcsec     mj              NVSS catalog fitted deconvolved  major axis (1)
181-189  I2      ---        mj_lim          Deconvolved  major axis upper limit flag, limit=-1, resolved=1  (1)
191-200  F8.2    arcsec     mn              NVSS catalog fitted deconvolved  minor axis (1)
202-210  I2      ---        mn_lim          Deconvolved  minor axis upper limit flag, limit=-1, resolved=1  (1)
212-221  F8.2    mJy        I_SP            S-PASS peak intensity 
223-232  F8.2    mJy        I_SP_err        S-PASS peak intensity uncertainty
234-243  F8.2    mJy        P_SP            S-PASS polarized intensity 
245-254  F8.2    mJy        P_SP_err        S-PASS polarized intensity uncertainty 
256-265  F8.4    ---        Pi_SP           S-PASS fractional polarization, In case of no detection the upper limit value is used.
267-276  F8.4    ---        Pi_SP_err       S-PASS fractional polarization uncertainty
278-286  I2      ---        Pi_SP_lim       S-PASS fractional polarization upper limit flag, limit=-1, detection=1
288-299  F10.4   deg        SP_pol_ang      S-PASS polarization angle 
301-312  F10.4   deg        SP_pol_ang_err  S-PASS polarization angle uncertainty 
314-323  F8.2    ---        Alpha           Spectral index derived from NVSS and S-PASS
325-334  F8.2    ---        Alpha_err       Spectral index uncertainty
336-345  F8.2    ---        Depol           ? Depolarization defined as Pi_SP/Pi_NV.  See Pi_SP_lim or Pi_NV_lim to determine whether upper limits were used.
347-356  F8.2    ---        Depol_err       ? Depolarization uncertainty
358-367  F8.2    rad.m^-2   RM_T            ? Taylor et al. 2009 rotation measure
369-378  F8.2    rad.m^-2   RM_T_err        ? Taylor et al. 2009 rotation measure uncertainty multiplied by 1.22 
380-389  F8.2    rad.m^-2   RM_NS           ? rotation measure derived from NVSS and S-PASS  
391-400  F8.2    rad.m^-2   RM_NS_err       ? NVSS_S-PASS rotation measure uncertainty 
402-411  F8.2    rad.m^-2   DeltaRM         ? The difference between the two rotation measures DeltaRM=RM_NS-RM_T 
413-422  F8.2    rad.m^-2   DeltaRM_err     ? DeltaRM uncertainty 
424-433  F8.2    rad.m^-2   MedRM_T         ? Median RM_T, extracted from Taylor et al. 2009 RM catalog with all objects within 3 degrees contributing to the median value
435-443  I2      ---        Num_MedRM       ? Number of sources contributed to the median RM_T
445-456  F6.4    ---        z               ? Redshift from Hammond et al. 2012
458-467  F8.2    mag        W1              ? WISE catalog W1 magnitude 
469-478  F8.2    mag        W1er            ? WISE W1 magitude uncertainty
480-489  F8.2    ---        W1snr           ? WISE W1 detection signal to noise ratio 
491-500  F8.2    mag        W2              ? WISE catalog W2 magnitude
502-511  F8.2    mag        W2er            ? WISE W2 magnitude uncertainty
513-522  F8.2    ---        W2snr           ? WISE W2 detection signal to noise ratio 
524-533  F8.2    mag        W3              ? WISE catalog W3 magnitude
535-544  F8.2    mag        W3er            ? WISE W3 magnitude uncertainty
546-555  F8.2    ---        W3snr           ? WISE W3 detection signal to noise ratio 
--------------------------------------------------------------------------------
Note (1): These are directly extracted from the NVSS catalog.
--------------------------------------------------------------------------------

Refrences:
	Condon, J. J., Cotton, W. D., Greisen, E. W., et al. 1998, AJ, 115, 1693
	Hammond, A. M., Robishaw, T., & Gaensler, B. M. 2012, ArXiv e-prints, arXiv:1209.1438
	Taylor, A. R., Stil, J. M., & Sunstrum, C. 2009, ApJ, 702, 1230
	Wright, E. L., Eisenhardt, P. R. M., Mainzer, A. K., et al. 2010, AJ, 140, 1868
================================================================================
(End)                            Mehdi Lamee [Minnesota Institute for Astrophysics, USA]     31-March-2016
     