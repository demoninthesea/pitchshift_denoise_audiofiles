<script type="text/x-mathjax-config"> MathJax.Hub.Config({ TeX: { equationNumbers: { autoNumber: "all" } } }); </script>
<script type="text/x-mathjax-config">
	MathJax.Hub.Config({
		tex2jax: {
			inlineMath: [ ['$','$'], ["\\(","\\)"] ],
      processEscapes: true
  }
});
</script>
<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

<!-- ... -->

<link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet" integrity="sha384-wvfXpqpZZVQGK6TAh5PVlGOfQNHSoD2xbE+QkPxCAFlNEevoEH3Sl0sibVcOQVnN" crossorigin="anonymous" />
<link rel="stylesheet" href="{{ site.baseurl}}/css/trackswitch.min.css" />




    
# Audio Examples

[toc]


## Chapter 2 - Fundamentals
 

### 2.1.1 Pitch Shifting Methods

"Andante" Reference sample. Spectrogram see Fig. 2.1 (left).
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/211_andante_ref.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/211_andante_ref.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

"Andante" sample with frequency magnitudes shifted upwards. Spectrogram in Fig. 2.1 (right).
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/211_andante_deepfried.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/211_andante_deepfried.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

C notes played from lowest (C1) to highest (C8). Spectrogram in Fig. 2.2.
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/211_c_tower.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/211_c_tower.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>


## Chapter 3 - Methods

### 3.2.1 Evaluation Dataset

All samples used throughout the thesis:

Andante
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/321_andante.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/321_andante.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

Saltsea
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/321_saltsea.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/321_saltsea.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

Boogie
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/321_boogie.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/321_boogie.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

Chords
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/321_chords.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/321_chords.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

Low Scale
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/321_lowscale.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/321_lowscale.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

Medium Scale
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/321_mediumscale.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/321_mediumscale.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

High Scale
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/321_highscale.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/321_highscale.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

Spaced
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/321_spaced.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/321_spaced.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>


## Chapter 4 - Experiments and Results

### 4.1 Digital artifacts caused by TSM pitch shifting

"Andante" sample with different pitch shifts $\Delta p$. Spectrograms in Fig. 4.2.

**MIDI shifted reference samples:**

$\Delta p=-12$
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/410_andante_p-12_ref.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/410_andante_p-12_ref.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

$\Delta p=-6$
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/410_andante_p-6_ref.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/410_andante_p-6_ref.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

$\Delta p=0$
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/410_andante_p0_ref.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/410_andante_p0_ref.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

$\Delta p=6$
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/410_andante_p6_ref.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/410_andante_p6_ref.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

$\Delta p=12$
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/410_andante_p12_ref.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/410_andante_p12_ref.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

**TSM shifted samples:**

$\Delta p=-12$
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/410_andante_p-12_baseline.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/410_andante_p-12_baseline.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

$\Delta p=-6$
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/410_andante_p-6_baseline.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/410_andante_p-6_baseline.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

$\Delta p=0$
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/410_andante_p0_baseline.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/410_andante_p0_baseline.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

$\Delta p=6$
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/410_andante_p6_baseline.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/410_andante_p6_baseline.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

$\Delta p=12$
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/410_andante_p12_baseline.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/410_andante_p12_baseline.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>


### 4.1.1 Upwards pitch shift

"Saltsea" sample with $\Delta p=12$.

Reference:
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/411_saltsea_p12_ref.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/411_saltsea_p12_ref.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

Baseline:
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/411_saltsea_p12_baseline.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/411_saltsea_p12_baseline.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>


### 4.2.1 Diffusion model results - No pitch shift

"Saltsea" sample with $\Delta p=0$ at different denoiser configurations. 

Reference (Spectrogram in Fig. 4.7 (right))
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/421_saltsea_p0_ref.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/421_saltsea_p0_ref.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

$t_0=1,\xi'=0$
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/421_saltsea_p0_xi0_T100.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/421_saltsea_p0_xi0_T100.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

$t_0=7/8,\xi'=0$
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/421_saltsea_p0_xi0_T88.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/421_saltsea_p0_xi0_T88.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

$t_0=5/8,\xi'=0$ (Spectrogram in Fig. 4.7 (left))
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/421_saltsea_p0_xi0_T63.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/421_saltsea_p0_xi0_T63.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

$t_0=1,\xi'=0.05$
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/421_saltsea_p0_xi05_T100.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/421_saltsea_p0_xi05_T100.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

$t_0=1,\xi'=0.2$
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/421_saltsea_p0_xi20_T100.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/421_saltsea_p0_xi20_T100.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>


### 4.2.2 Diffusion model results - Upwards pitch shift

#### "Saltsea", $\Delta p=3$
Reference:
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p3_ref.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p3_ref.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

Baseline:
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p3_baseline.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p3_baseline.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

$t_0=1,\xi'=0.4$
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p3_xi40_T100.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p3_xi40_T100.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

$t_0=5/8,\xi'=0.3$
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p3_xi30_T63.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p3_xi30_T63.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

$t_0=3/8,\xi'=0.3$
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p3_xi30_T38.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p3_xi30_T38.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

$t_0=1/2,\xi'=0.2$
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p3_xi20_T50.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p3_xi20_T50.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

#### "Saltsea", $\Delta p=6$
Reference:
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p6_ref.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p6_ref.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

Baseline:
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p6_baseline.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p6_baseline.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

$t_0=3/4,\xi'=0.25$
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p6_xi25_T75.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p6_xi25_T75.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

#### "Saltsea", $\Delta p=9$
Reference:
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p9_ref.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p9_ref.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

Baseline:
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p9_baseline.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p9_baseline.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

$t_0=3/4,\xi'=0.25$
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p9_xi20_T88.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p9_xi20_T88.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

#### "Saltsea", $\Delta p=12$
Reference:
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p12_ref.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p12_ref.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

Baseline:
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p12_baseline.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p12_baseline.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

$t_0=1/2,\xi'=0$
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p12_xi0_T50.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p12_xi0_T50.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

$t_0=5/8,\xi'=0$
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p12_xi0_T63.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p12_xi0_T63.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

$t_0=3/4,\xi'=0.15$
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p12_xi15_T75.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p12_xi15_T75.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

$t_0=7/8,\xi'=0.3$
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p12_xi30_T88.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/422_saltsea_p12_xi30_T88.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

#### "Medium Scale", $\Delta p=12$
Reference:
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/422_mediumscale_p12_ref.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/422_mediumscale_p12_ref.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

Baseline:
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/422_mediumscale_p12_baseline.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/422_mediumscale_p12_baseline.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

$t_0=3/4,\xi'=0.15$
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/422_mediumscale_p12_xi15_T75.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/422_mediumscale_p12_xi15_T75.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

#### "Boogie", $\Delta p=12$
Reference:
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/422_boogie_p12_ref.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/422_boogie_p12_ref.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

Baseline:
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/422_boogie_p12_baseline.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/422_boogie_p12_baseline.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

$t_0=3/4,\xi'=0.15$
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/422_boogie_p12_xi15_T75.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/422_boogie_p12_xi15_T75.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>



### 4.2.3 Diffusion model results - Downwards pitch shift

#### "Saltsea", $\Delta p=-3$
Reference:
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/423_saltsea_p-6_ref.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/423_saltsea_p-6_ref.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

Baseline:
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/423_saltsea_p-6_baseline.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/423_saltsea_p-6_baseline.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

$t_0=1/2,\xi'=0.05$
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/423_saltsea_p-6_xi05_T50.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/423_saltsea_p-6_xi05_T50.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

#### "Saltsea", $\Delta p=-6$
Reference:
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/423_saltsea_p-6_ref.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/423_saltsea_p-6_ref.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

Baseline:
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/423_saltsea_p-6_baseline.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/423_saltsea_p-6_baseline.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

$t_0=5/8,\xi'=0.05$
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/423_saltsea_p-6_xi05_T63.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/423_saltsea_p-6_xi05_T63.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

#### "Saltsea", $\Delta p=-9$
Reference:
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/423_saltsea_p-9_ref.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/423_saltsea_p-9_ref.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

Baseline:
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/423_saltsea_p-9_baseline.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/423_saltsea_p-9_baseline.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

$t_0=3/8,\xi'=0.05$
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/423_saltsea_p-9_xi05_T38.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/423_saltsea_p-9_xi05_T38.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

#### "Saltsea", $\Delta p=-12$
Reference:
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/423_saltsea_p-12_ref.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/423_saltsea_p-12_ref.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

Baseline:
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/423_saltsea_p-12_baseline.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/423_saltsea_p-12_baseline.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>

$t_0=5/8,\xi'=0.05$
<audio controls>
  <source src="{{ site.baseurl}}/examples/sounds/423_saltsea_p-12_xi05_T63.wav" type="audio/ogg">
  <source src="{{ site.baseurl}}/examples/sounds/423_saltsea_p-12_xi05_T63.wav" type="audio/mpeg">
  Your browser does not support the audio tag. 
</audio>





