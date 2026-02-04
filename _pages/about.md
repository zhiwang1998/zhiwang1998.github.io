---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


Bio 🎓
======
I am a PhD candidate at Institute of Software, Chinese Academy of Sciences, advised by Prof. Beihong Jin and Prof. Fusang Zhang. I received my B.S. degree from Beijing Jiaotong University in 2020.

I am interested in wireless sensing and mobile computing for cardiovascular health monitoring. More recently, I focus on the privacy and security challenges within wireless sensing.


News 🔥
======
- **Feb 2026** Waiting for good news!


Selected Publications 📑
======
- <span style="background-color: #961c1c; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: 600;font-size: 0.8em">UbiComp '25</span>
  [RF-AE: Single-site Arterial Elasticity Estimation Using UWB Signals](https://dl.acm.org/doi/abs/10.1145/3729460)
  <br>
  **<u>Zhi Wang</u>**, Beihong Jin, Yuhui Chen, Fusang Zhang, Siheng Li, Junqi Ma, Tao Gong, Yu Fu.
  <br>
  *Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies (IMWUT/UbiComp)*
  <br>
  <details style="cursor: pointer;margin-bottom: 1em;">
    <summary style="font-size: 0.9em; color: #666; font-weight: bold;">Abstract</summary>
    <div style="margin-top: 10px; padding: 10px; background: #f9f9f9; border-left: 3px solid #961c1c; font-size: 0.95em; color: #444;">
      Arterial elasticity is the capability of the arteries to dilate and constrict in response to fluctuations in blood pressure as the heart circulates blood throughout the body, serving as an important indicator for assessing arterial health. However, conventional medical detection methods are often complex, costly, and require direct contact between the user's skin and the device, making them impractical for regular monitoring. In this paper, we propose a contactless single-site arterial elasticity assessment approach using ultra-wideband (UWB) signals, where we estimate the brachial-ankle pulse wave velocity, a key indicator of arterial health, by analyzing the UWB signals reflected off the back of a subject sitting still. Specifically, we first propose preprocessing methods to reduce noise in the received UWB signals, and then design a deep generative adversarial network to generate pulse wave signals from these UWB signals. The generated signals are of high quality and fidelity, exhibiting characteristics of vasoconstriction and vasodilation. Further, we analyze the pulse wave and extract the features related to arterial elasticity from the generated pulse waves. Finally, we employ random forest regression to predict pulse transit time and a body-height based method to estimate the length of the pulse transit path, so as to achieve single-site arterial elasticity assessment. We build the corresponding system named RF-AE and conduct extensive experiments to evaluate its performance. The experimental results show that RF-AE can accurately predict the arterial elasticity of users.
    </div>
  </details>

- <span style="background-color: #961c1c; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: 600;font-size: 0.8em">UbiComp '24</span>
  [Hypnos: A contactless sleep stage monitoring system using UWB signals](https://dl.acm.org/doi/abs/10.1145/3678581)
  <br>
  Siheng Li, Beihong Jin, Fusang Zhang, **<u>Zhi Wang</u>**, Junqi Ma, Xiaoyong Ren, Haiqin Liu.
  <br>
  *Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies (IMWUT/UbiComp)*
  <br>
  <details style="cursor: pointer;margin-bottom: 1em;">
    <summary style="font-size: 0.9em; color: #666; font-weight: bold;">Abstract</summary>
    <div style="margin-top: 10px; padding: 10px; background: #f9f9f9; border-left: 3px solid #961c1c; font-size: 0.95em; color: #444;">
      As a fundamental physiological process, sleep plays a vital role in human health. High-quality sleep requires a reasonable distribution of sleep duration over different sleep stages. Recently, contactless solutions have been used for in-home sleep stage monitoring via wireless signals as it enables monitoring daily sleep in a non-intrusive manner. However, various factors, such as the subject's physiological characteristics during sleep, the subject's health status, and even the sleep environment, pose challenges to wireless signal analysis. In this paper, we propose Hypnos, a contactless sleep monitoring system that identifies different sleep stages using an ultra-wideband (UWB) device. Hypnos enables automated bed localization and extracts signals containing coarse-grained body movements and fine-grained chest movements due to breathing and heartbeat from the subject, which acts as the preparation step for sleep staging. The key to our system is a seq2seq deep learning model, which adopts an attention-based sequence encoder to learn the patterns and transitions within and between sleep epochs and combines with contrastive learning to improve the generalizability of the encoder. Particularly, we incorporate sleep apnea detection as an auxiliary task into the model to reduce the interference of sleep apnea with sleep staging. Moreover, we design a two-step training for better adaptation of subjects with different severities of sleep disorders. We conduct extensive experiments on 100 subjects, including healthy individuals and patients with sleep disorders, and the experimental results show that Hypnos achieves excellent performance in multi-stage sleep classification (including 5-stage sleep classification), and outperforms other baseline methods.    </div>
  </details>
  
- <span style="background-color: #961c1c; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: 600;font-size: 0.8em">UbiComp '24</span>
  [Push the limit of highly accurate ranging on commercial uwb devices](https://dl.acm.org/doi/abs/10.1145/3659602)
  <br>
  Junqi Ma, Fusang Zhang, Beihong Jin, Chang Su, Siheng Li, **<u>Zhi Wang</u>**, Jiazhi Ni.
  <br>
  *Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies (IMWUT/UbiComp)*
  <br>
  <details style="cursor: pointer;margin-bottom: 1em;">
    <summary style="font-size: 0.9em; color: #666; font-weight: bold;">Abstract</summary>
    <div style="margin-top: 10px; padding: 10px; background: #f9f9f9; border-left: 3px solid #961c1c; font-size: 0.95em; color: #444;">
      Ranging plays a crucial role in many wireless sensing applications. Among the wireless techniques employed for ranging, Ultra-Wideband (UWB) has received much attention due to its excellent performance and widespread integration into consumer-level electronics. However, the ranging accuracy of the current UWB systems is limited to the centimeter level due to bandwidth limitation, hindering their use for applications that require a very high resolution. This paper proposes a novel system that achieves sub-millimeter-level ranging accuracy on commercial UWB devices for the first time. Our approach leverages the fine-grained phase information of commercial UWB devices. To eliminate the phase drift, we design a fine-grained phase recovery method by utilizing the bi-directional messages in UWB two-way ranging. We further present a dual-frequency switching method to resolve phase ambiguity. Building upon this, we design and implement the ranging system on commercial UWB modules. Extensive experiments demonstrate that our system achieves a median ranging error of just 0.77 mm, reducing the error by 96.54% compared to the state-of-the-art method. We also present three real-life applications to showcase the fine-grained sensing capabilities of our system, including i) smart speaker control, ii) free-style user handwriting, and iii) 3D tracking for virtual-reality (VR) controllers.
    </div>
  </details>
  
- <span style="background-color: #961c1c; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: 600;font-size: 0.8em">UbiComp '24</span>
  [Uwb-enabled sensing for fast and effortless blood pressure monitoring](https://dl.acm.org/doi/abs/10.1145/3659617)
  <br>
  **<u>Zhi Wang</u>**, Beihong Jin, Fusang Zhang, Siheng Li, Junqi Ma.
  <br>
  *Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies (IMWUT/UbiComp)*
  <br>
  <details style="cursor: pointer;margin-bottom: 1em;">
    <summary style="font-size: 0.9em; color: #666; font-weight: bold;">Abstract</summary>
    <div style="margin-top: 10px; padding: 10px; background: #f9f9f9; border-left: 3px solid #961c1c; font-size: 0.95em; color: #444;">
      Blood Pressure (BP) is a critical vital sign to assess cardiovascular health. However, existing cuff-based and wearable-based BP measurement methods require direct contact between the user's skin and the device, resulting in poor user experience and limited engagement for regular daily monitoring of BP. In this paper, we propose a contactless approach using Ultra-WideBand (UWB) signals for regular daily BP monitoring. To remove components of the received signals that are not related to the pulse waves, we propose two methods that utilize peak detection and principal component analysis to identify aliased and deformed parts. Furthermore, to extract BP-related features and improve the accuracy of BP prediction, particularly for hypertensive users, we construct a deep learning model that extracts features of pulse waves at different scales and identifies the different effects of features on BP. We build the corresponding BP monitoring system named RF-BP and conduct extensive experiments on both a public dataset and a self-built dataset. The experimental results show that RF-BP can accurately predict the BP of users and provide alerts for users with hypertension. Over the self-built dataset, the mean absolute error (MAE) and standard deviation (SD) for SBP are 6.5 mmHg and 6.1 mmHg, and the MAE and SD for DBP are 4.7 mmHg and 4.9 mmHg.
    </div>
  </details>

- <span style="background-color: #961c1c; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: 600;font-size: 0.8em">UbiComp '24</span>
  [Embracing distributed acoustic sensing in car cabin for children presence detection](https://dl.acm.org/doi/abs/10.1145/3643548)
  <br>
  Yuqi Su, Fusang Zhang, Kai Niu, Tianben Wang, Beihong Jin, **<u>Zhi Wang</u>**, Yalan Jiang, Daqing Zhang, Lili Qiu, Jie Xiong.
  <br>
  *Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies (IMWUT/UbiComp)*
  <br>
  <details style="cursor: pointer;margin-bottom: 1em;">
    <summary style="font-size: 0.9em; color: #666; font-weight: bold;">Abstract</summary>
    <div style="margin-top: 10px; padding: 10px; background: #f9f9f9; border-left: 3px solid #961c1c; font-size: 0.95em; color: #444;">
      Contactless acoustic sensing has been actively exploited in the past few years to enable a large range of applications, ranging from fine-grained vital sign monitoring to coarse-grained human tracking. However, existing acoustic sensing systems mainly work on smartphone or smart speaker platforms. In this paper, we envision an exciting new acoustic sensing platform, i.e., car cabin which is inherently embedded with a large number of speakers and microphones. We propose the new concept of distributed acoustic sensing and develop novel designs leveraging the unique characteristics of rich multi-path in car cabin to enable fine-grained sensing even when the primary reflection is totally blocked. By using child presence detection as the application example, we show that child presence can be detected through body motions or even subtle breath (when the child is sleeping or in coma) at all locations in the cabin without any blind spots. We further show that the proposed system can robustly work in different car cabins, achieving an average detection accuracy of 97% and a false alarm rate always below 2% under different scenarios including those challenging ones such as rear-facing seat blockage. We believe the proposed distributed sensing modality in car cabin pushes acoustic sensing one big step towards real-life adoption.
    </div>
  </details>
  
- <span style="background-color: #961c1c; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: 600;font-size: 0.8em">UbiComp '23</span>
  [ECG-grained cardiac monitoring using uwb signals](https://dl.acm.org/doi/abs/10.1145/3569503)
  <br>
  **<u>Zhi Wang</u>**, Beihong Jin, Siheng Li, Fusang Zhang, Wenbo Zhang.
  <br>
  *Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies (IMWUT/UbiComp)*
  <br>
  <details style="cursor: pointer;margin-bottom: 1em;">
    <summary style="font-size: 0.9em; color: #666; font-weight: bold;">Abstract</summary>
    <div style="margin-top: 10px; padding: 10px; background: #f9f9f9; border-left: 3px solid #961c1c; font-size: 0.95em; color: #444;">
      With the development of wireless sensing, researchers have proposed many contactless vital sign monitoring systems, which can be used to monitor respiration rates, heart rates, cardiac cycles and etc. However, these vital signs are ones of coarse granularity, so they are less helpful in the diagnosis of cardiovascular diseases (CVDs). Considering that electrocardiogram (ECG) is an important evidence base for the diagnoses of CVDs, we propose to generate ECGs from ultra-wideband (UWB) signals in a contactless manner as a fine-grained cardiac monitoring solution. Specifically, we analyze the properties of UWB signals containing heartbeats and respiration, and design two complementary heartbeat signal restoration methods to perfectly recover heartbeat signal variation. To establish the mapping between the mechanical activity of the heart sensed by UWB devices and the electrical activity of the heart recorded in ECGs, we construct a conditional generative adversarial network to encode the mapping between mechanical activity and electrical activity and propose a contrastive learning strategy to reduce the interference from noise in UWB signals. We build the corresponding cardiac monitoring system named RF-ECG and conduct extensive experiments using about 120,000 heartbeats from more than 40 participants. The experimental results show that the ECGs generated by RF-ECG have good performance in both ECG intervals and morphology compared with the ground truth. Moreover, diseases such as tachycardia/bradycardia, sinus arrhythmia, and premature contractions can be diagnosed from the ECGs generated by our RF-ECG.
    </div>
  </details>
  
- <span style="background-color: #8A2BE2; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: 600; font-size: 0.8em">BIBM '22</span>
  [Sleep respiration monitoring using attention-reinforced radar signals](https://ieeexplore.ieee.org/abstract/document/9995437/)
  <br>
  Siheng Li, **<u>Zhi Wang</u>**, Beihong Jin, Fusang Zhang, Xiaoyong Ren, Yitong Zhang.
  <br>
  *IEEE International Conference on Bioinformatics and Biomedicine (BIBM)*
  <br>
  <details style="cursor: pointer;margin-bottom: 1em;">
    <summary style="font-size: 0.9em; color: #666; font-weight: bold;">Abstract</summary>
    <div style="margin-top: 10px; padding: 10px; background: #f9f9f9; border-left: 3px solid #8A2BE2; font-size: 0.95em; color: #444;">
      Existing contactless solutions on sleep respiration monitoring are either performed in controlled environments, having poor usability in practical scenarios, or only provide coarse-grained respiration rates, being unable to accurately detect abnormal events of patients. In this paper, we propose Respnea, a non-invasive sleep respiration monitoring system using an impulse-radio ultra-wideband (IR-UWB) radar. Particularly, we propose a profiling algorithm, which can locate the sleep positions in non-controlled environments and identify different states of subjects. Further, we construct a deep learning model which adopts a multi-headed self-attention and learn the patterns implicit in the respiration signal so as to distinguish sleep respiration events at a granularity of seconds. We conduct experiments on data collected from patients with sleep disorders and healthy subjects. The experimental results show that Respnea achieves a low error (less than 0.27 bpm) in respiration rate estimation and reaches the accuracy of 88.89% diagnosing the severity of Sleep Apnea-Hypopnea Syndrome.
    </div>
  </details>

- <span style="background-color: #2e7d32; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: 600;font-size: 0.8em">Globecom '21</span>
  [Exploiting passive beamforming of smart speakers to monitor human heartbeat in real time](https://ieeexplore.ieee.org/abstract/document/9685922/)
  <br>
  **<u>Zhi Wang</u>**, Fusang Zhang, Siheng Li, Beihong Jin.
  <br>
  *IEEE Global Communications Conference (GLOBECOM)*
  <br>
  <details style="cursor: pointer;margin-bottom: 1em;">
    <summary style="font-size: 0.9em; color: #666; font-weight: bold;">Abstract</summary>
    <div style="margin-top: 10px; padding: 10px; background: #f9f9f9; border-left: 3px solid #2e7d32; font-size: 0.95em; color: #444;">
      Currently, cardiac diseases have become one of the biggest health concerns. Existing heartbeat monitoring methods either require dedicated intrusive devices (e.g., ECG devices) that suffer high costs or leverage video camera analyses that are light-sensitive. In this paper, leveraging the acoustic signals sent by a speaker and received by a microphone array, we develop a prototype system to achieve the contactless and low-cost heartbeat monitoring. In particular, while we exploit the passive beamforming to enhance the user's heartbeat signal, we design a filtering method in frequency domain to remove the line-of-sight (LoS) impact and retain the target-reflected signals, and propose a wideband time-delay method to estimate the direction of arrival of target-reflected signal. Thus, our prototype is able to robustly estimate the human heartbeat and push the limit of acoustic sensing range. The experimental results show that our prototype achieves a heart rate monitoring at 1.7 m with the estimation error of 0.5 bpm, which is comparable to ECG or other contact-based solutions.
    </div>
  </details>
  
- <span style="background-color: #961c1c; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: 600;font-size: 0.8em">UbiComp '21</span>
  [Your Smart Speaker Can" Hear" Your Heartbeat!](https://dl.acm.org/doi/abs/10.1145/3432237)
  <br>
  Fusang Zhang<sup>&#42;</sup>, **<u>Zhi Wang</u>**<sup>&#42;</sup>, Beihong Jin, Jie Xiong, Daqing Zhang.
  <br>
  *Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies (IMWUT/UbiComp)*
  <br>
  <details style="cursor: pointer;margin-bottom: 1em;">
    <summary style="font-size: 0.9em; color: #666; font-weight: bold;">Abstract</summary>
    <div style="margin-top: 10px; padding: 10px; background: #f9f9f9; border-left: 3px solid #961c1c; font-size: 0.95em; color: #444;">
      Vital sign monitoring is a common practice amongst medical professionals, and plays a key role in patient care and clinical diagnosis. Traditionally, dedicated equipment is employed to monitor these vital signs. For example, electrocardiograms (ECG) with 3-12 electrodes are attached to the target chest for heartbeat monitoring. In the last few years, wireless sensing becomes a hot research topic and wireless signal itself is utilized for sensing purposes without requiring the target to wear any sensors. The contact-free nature of wireless sensing makes it particularly appealing in current COVID-19 pandemic. Recently, promising progress has been achieved and the sensing granularity has been pushed to millimeter level, fine enough to monitor respiration which causes a chest displacement of 5 mm. While a great success with respiration monitoring, it is still very challenging to monitor heartbeat due to the extremely subtle chest displacement (0.1 - 0.5 mm) - smaller than 10% of that caused by respiration. What makes it worse is that the tiny heartbeat-caused chest displacement is buried inside the respiration-caused displacement. In this paper, we show the feasibility of employing the popular smart speakers (e.g., Amazon Echo) to monitor an individual's heartbeats in a contact-free manner. To extract the submillimeter heartbeat motion in the presence of other interference movements, a series of novel signal processing schemes are employed. We successfully prototype the first real-time heartbeat monitoring system using a commodity smart speaker. Experiment results show that the proposed system can monitor a target's heartbeat accurately, achieving a median heart rate estimation error of 0.75 beat per minute (bpm), and a median heartbeat interval estimation error of 13.28 ms (less than 1.8%), outperforming even some popular commodity products available on the market.
    </div>
  </details>

  






