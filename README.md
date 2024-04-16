# Wealthsimple Formal Model
Modeling and validation project for EECS4315 mission critical systems

# Requirements
This project requires the CADP toolbox (https://cadp.inria.fr)

# How to run
Run full state coverage with validation:
```
svl demo
```

Run on-the-fly with custom maxBalance and maxStock parameters:
```
lnt.open -root 'Main([maxBalance],[maxStock])' WealthSimple.lnt ocis
```

# Model Architecture
![image](https://github.com/xzippyzachx/wealthsimple-formal-model/assets/33043402/6f7703a4-c5ae-425e-a211-37512323d44b)

# Version History
The [Version History](https://github.com/xzippyzachx/wealthsimple-formal-model/tree/main/VersionHistory) contains the iteration of lnt as we developed each iteration of the model (m0-m2) and the iteration of lnt as we fixed issues found during validation (v0-v2)

# Contributors
- Ahmed El Dib
- Walid AlDari
- Zachary Ross
