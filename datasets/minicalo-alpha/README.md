## minicalo-alpha
This dataset is based on small GEANT based calorimeter which shows same problems as HGCal (sparsity and non-homogenous).

You can find the simulator over here:

```bash
https://github.com/jkiesele/miniCalo
```


### Fraction
How much of energy deposit belongs to the shower of the particle.

### Particles
1. Electron
2. Muon
3. Charged Pion
4. Neutral Pion
5. K0 Long
6. K0 Short

### Energy range

The energy varies from 0-100 GeV

### Pileup

No pileup in the data. All the rechits correspond to the one single particle that is shot into the calorimeter.

### Starter code

_TODO: Add starter code_

### Experiments

1. Particle Classification
2. Energy regression

### EOS
The dataset can be found in root format in this directory
```bash
/eos/cms/store/cmst3/group/dehep/miniCalo/prod3
```

### Number of events
There are 6000000 events (1m for each of the particle).