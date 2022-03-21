# Haemodynamic-Response-Mapper
VU Brain Imaging 2022. Group 16

# TODO:
1. What to do with veins? "we're looking at blood, and at 7 Tesla (at which all these data were acquired) these veins show up very strongly. Their presence has a strong influence on whether you can find any 'activation', as they may get in the way of what you want to find. Keep this in mind!"
2. Make data description
3. additional preprocessing, such as temporal filtering, percent signal change conversion, etc.?
   1. z-tranform is applied on t_series - confirmed
   2. drift/trend to check with linear model SLOW DRIFT (Abdi and Lef). Do we need another drift?
   3. have raw data been spacially smoothed?
4. Switch modelling to sklearn/torch? (Oleg)
