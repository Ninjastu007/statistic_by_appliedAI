# statistic_by_appliedAI
A/B test -> samplingTech


# Q1 :  why shuflling in Permutation testing ? IF there is no shuffle then ? ( A/B test ) 

-> if we don't shuffle then there may be chances of getting same element/obs in each iteration and there will be high chances that their mean is always approx eqal to the 
observed_mean_diff  = ( mean(xT) - mean(xC) ) ; 
- possible outcomes : probability => p( m >= 20 | xc=xt ) = very high 
- Even if you repeate the operation 'K' times then diffn( no_shuufled xt - non_shuffle_xc ) == ( mean (xt)  - mean (xc) ) .
- purely , Non probabilistic intitution / biased sampled
- Hence to avoid all above situations we use random sampling / shuffleing datasett 


🪚 power of permutation : 
Simulation | proof test 
 🖊️ resampling test | 🖊️ t-test
