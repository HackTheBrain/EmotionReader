# EmotionReader
Hackaton Hack-The-Brain project of reading emotion in real time with Biosemi ActiveTwo EEG.
Emotion recognition could be done from the text, speech, facial expression or gesture. In this project, we concentrate on recognition of “inner” emotions from EEG signals. We propose real time fractal dimension based algorithm of quantification of basic emotion using valence emotion model. The subject emotions are recognized and visualized in real time on avatar’s head through LED diodes which simulate every single electrode.

## Who are we?
+We are three enthusiasts people. 
+Eva Matuchová is psychology student, she cared about "paperwork", food, drinks and everything what wasn’t connected with programming.
+Michael Tesař is also psychology student, developer for EEG and fMRI and OpenSesame enthusiast. He created desing and brought it to live. 
+Michal Lenc is creative and artistic part of our team. He created LED diode belt and he brought it to live.

## Why we choose this project...
Our project could by used at many cases of medical field, professional or every day life. Generally BCI could be used for pilots or drivers and it could improve their professional skills. Avoid and prevent losing focus by visualizing valence and arousal during their work performance. It could be also useful as some kind of feedback for gaming, music, interactive arts, relaxation or books to show valence reactions to those stimuli in real time. In the medical field it could be used in psychotherapy or shows pathology at perception, processing information, recognition and reaction to positive or negative (pleasant, unpleasant) visual stimuli.

## Alpha Asymmetry
The most directly associated with emotions are prefrontal areas. Specifically ventrolateral region of prefrontal cortex and dorsolateral cortex which is most likely directly reflected in the scalp signals (Fp1 and Fp2 electrodes) from which metrics of functional prefrontal asymmetry are constructed. 

Frontal asymmetry in alpha oscillations is assumed to be associated with individual differences in emotional responding. Brain activity based feedback is a promising tool for the modulation of cortical activity. It refers to the average difference in brain activity between the left and right frontal areas, measured as hemispheric differences in alpha power in electroencephalography recordings across several minutes.  Activity in the left frontal hemisphere has been linked to an approach system that is activated when an individual is moving towards goals or experiences positive emotions. Conversely, a right lateralised withdrawal system is involved in negative affect or the motivation to move away from potentially dangerous situations or stimuli.
 

## Stimuli
For affective stimulation were used series of visual stimuli with different valence values. Those visual stimuli were taken from NAPS database which was was standardized on a set of 300 people. Stimuli were represented by 60 pictures which have been selected according to these values for three groups, 20 images for every group. Generally labeled as a positive, negative and neutral pictures. Subject was exposure for each picture until they rate it as negative, positive or neutral by pressing specific key. Between every picture was showed for 1 s. fixation cross to relax and move subject’s intention from previous picture to another one. 
Valence could reach values from 0 to 10. Visual stimuli for the experiment have been selected according to these values. Pictures with high level of valence (v>6.32) were tagged as positive. Pictures with level of valence (<3.66) were tagged as negative. The neutral pictures had neutral level of valence (=5). Pictures were equally divided according to their valence values. During distribution of pictures was taken into account that set includes the 5 types of pictures – faces, people, animals, objects and landscapes

## Hardware & Software
### Hardware
Acquistion of electroencephalographic (EEG) cerebral activity is recorded by Biosemi ActiveTwo system. It was collected scalp signal from 32 active channels. EEG montage was performed by ten-twenty international electrode placement system of measurement with Cz as central electrode and two CMS and DRL reference channels (recording is reference free). 

For online visualization was used LED diodes belt specifically changed and adapted for our project. Every single LED diode simulate at avatar’s head one of 32 active EEG channels. Reference electrodes included.
###Programming Languague
OpenVibe, Python, Arduino, OpenSesame, CodeLite, C++ 

##Ethic
Beneficience 
Potential harm could be caused by not following ethic standards, guidelines for using EEG, or misuse our idea. The steps we did to maximize benefits of our projects are described below. Our project could by used at many cases of medical field, professional or every day life. Generally BCI could be used for pilots or professional drivers and it could improve their skills. Avoid and prevent losing focus by visualizing valence and arousal during their work performance. It could be also useful as some kind of feedback for gaming, music, interactive arts, relaxation or books, to show valence reactions to those stimuli in real time. In the medical field it could shows pathology at perception, processing information, recognition and reaction to positive or negative (pleasant, unpleasant) visual stimuli.

Coercion 
We could choose specific stimuli for every individual according to light visualization of their specific valence values and preferences obvious from frontal alpha asymmetry. We don’t use any kind of coercion in our experiment.

Enhancement
Our project could by used at many cases of medical field, professional or every day life. Generally BCI could be used for pilots or professional drivers and it could improve their skills. Avoid and prevent losing focus by visualizing valence and arousal during their work performance. It could be also useful as some kind of feedback for gaming, music, interactive arts, or books to show valence reactions to those stimuli in real time. In the medical field it could shows pathology at perception, processing information, recognition and reaction to positive or negative (pleasant, unpleasant) visual stimuli.
Protection
Protection depends on specific situation of using this project.  EEG measuring isn’t recommended for pregnant women and people with any open head injury of wounds.
Accountability
All presented pictures come from IAPS (international affective picture system). All codes were made in Python and Open Vibe by Michael Tesař and idea of light visualization was realized by Michal Lenc.
Responsibility
All responsibily belongs to Eva Matuchová, Michael Tesař and Michal Lenc.
Vulnerability
All participants have to be completely healthy, physically and psychically and give us informed consent. Also we follow ethic code. EEG measuring isn’t recommended for pregnant women and people with any open head injury of wounds.
Autonomy – self government 
Emotions are very specific and individual. There aren’t two people who would feel exactly same emotions during two identical stimulation. Emotional experience depends on many factors, like participants experience, biological specific any many others. It means that’s complicated to work and analyze individuals emotion, but nor impossible.
Consent
Informed consent is required.
Privacy 
Privacy of users depends on type of use. EEG measuring could be anonymous so noone has to be afraid of their privacy.

