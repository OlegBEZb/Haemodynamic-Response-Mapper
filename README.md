# Haemodynamic-Response-Mapper
VU Brain Imaging 2022. Group 16

# TODO:
1. What to do with veins? "we're looking at blood, and at 7 Tesla (at which all these data were acquired) these veins show up very strongly. Their presence has a strong influence on whether you can find any 'activation', as they may get in the way of what you want to find. Keep this in mind!"
2. Make data description
3. additional preprocessing, such as temporal filtering, percent signal change conversion, etc.?
4. Switch modelling to sklearn/torch?

---about 3: preprocessing: \\
raw data z scored? was not!. done (var: tseries_z) \
is there slow drift in raw data? [ will be checked by lef/abdallah] \ 
have raw data been spacially smoothed? 
