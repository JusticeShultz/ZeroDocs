 `Sound`

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
| |[ AttackMillisec](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/expandernode.markdown#attackmillisec-zero-engi)|[soundnode](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/soundnode.markdown)| |
| |[ InputGainDecibels](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/expandernode.markdown#inputgaindecibels-zero-e)| | |
| |[ KneeWidth](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/expandernode.markdown#kneewidth-zero-engine-do)| | |
| |[ OutputGainDecibels](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/expandernode.markdown#outputgaindecibels-zero)| | |
| |[ Ratio](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/expandernode.markdown#ratio-zero-engine-docume)| | |
| |[ ReleaseMillisec](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/expandernode.markdown#releasemillisec-zero-eng)| | |
| |[ ThresholdDecibels](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/class_reference/expandernode.markdown#thresholddecibels-zero-e)| | |


 #  Properties


---  
 #  AttackMillisec : [real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/zilch_base_types/real.markdown)

> The time for the expander to ramp to full effect after the input reaches the threshold.
> ``` lang=cpp, name=Zilch
> var AttackMillisec : Real


---  
 #  InputGainDecibels : [real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/zilch_base_types/real.markdown)

> The volume adjustment applied to the audio input, in decibels.
> ``` lang=cpp, name=Zilch
> var InputGainDecibels : Real


---  
 #  KneeWidth : [real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/zilch_base_types/real.markdown)

> The knee width of the expander, in decibels.
> ``` lang=cpp, name=Zilch
> var KneeWidth : Real


---  
 #  OutputGainDecibels : [real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/zilch_base_types/real.markdown)

> The volume adjustment applied to the expander output, in decibels.
> ``` lang=cpp, name=Zilch
> var OutputGainDecibels : Real


---  
 #  Ratio : [real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/zilch_base_types/real.markdown)

> The ratio of the volume reduction applied by the expander.
> ``` lang=cpp, name=Zilch
> var Ratio : Real


---  
 #  ReleaseMillisec : [real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/zilch_base_types/real.markdown)

> The time for the expander to ramp from full effect to off after the input goes above the threshold.
> ``` lang=cpp, name=Zilch
> var ReleaseMillisec : Real


---  
 #  ThresholdDecibels : [real](https://github.com/zeroengineteam/ZeroDocs/blob/master/code_reference/zilch_base_types/real.markdown)

> The threshold, in decibels, at which the volume of the input is affected by the expander.
> ``` lang=cpp, name=Zilch
> var ThresholdDecibels : Real


---  
 #  Methods


---  
 

 