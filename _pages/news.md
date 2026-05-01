---
permalink: /news/
title: "News"
author_profile: true
---

<style>
.older-news {
  display: none;
}

.toggle-button {
  background: #f8f9fa;
  border: 1px solid #dee2e6;
  border-radius: 4px;
  padding: 8px 16px;
  margin: 20px 0;
  cursor: pointer;
  display: inline-block;
  color: #495057;
  font-size: 14px;
  transition: background-color 0.2s;
  user-select: none;
}

.toggle-button:hover {
  background: #e9ecef;
}
</style>

<script>
function toggleNews() {
  var olderNews = document.querySelector('.older-news');
  var button = document.querySelector('.toggle-button');
  
  if (olderNews.style.display === 'none' || olderNews.style.display === '') {
    olderNews.style.display = 'block';
    button.textContent = 'Hide older news...';
  } else {
    olderNews.style.display = 'none';
    button.textContent = 'Show older news...';
  }
}
</script>

## Recent News
- <b>[Apr 2026]</b> Our paper on real-time intrusion detection for IoMT with SmartNICs was accepted to the Workshop on Edge Network Softwarization (ENS), co-located with IEEE NetSoft 2026.
- <b>[Apr 2026]</b> Our paper on remote patient monitoring with in-network ML on IoMT gateways was accepted to the IEEE Internet of Things Journal.
- <b>[Mar 2026]</b> Our paper on hybrid in-network inference in SmartNICs (HyNIC) was accepted to IEEE NetSoft 2026.
- 🏆 <b>[Dec 2025]</b> My PhD thesis received the <b>Outstanding Doctoral Thesis (PhD) Award</b> from Universidad Carlos III de Madrid.
- <b>[Sep 2025]</b> <b>New Chapter!</b> I joined the University of Southampton as a Lecturer in Computer Science.
- <b>[Aug 2025]</b> I was invited to the Technical Program Committee for the Passive and Active Measurement Conference (PAM) 2026.
- 🏆 <b>[May 2025]</b> My PhD thesis received the <b>Best Doctoral Thesis (PhD) Award</b> from the IEEE Spain Signal Processing and Communications Joint Chapter.

<div class="toggle-button" onclick="toggleNews()">Show older news...</div>

<div class="older-news">

<h2>Older News</h2>
<ul>
<li><b>[May 2025]</b> I attended the 2025 IEEE International Conference on Machine Learning for Communication and Networking (ICMLCN), 26–29 May 2025, Barcelona, Spain.</li>
<li><b>[April 2025]</b> Our paper "Practical and General-Purpose Flow-Level Inference with Random Forests in Programmable Switches" was accepted for publication in the IEEE/ACM Transactions on Networking.</li>
<li><b>[Feb 2025]</b> <b>New Chapter!</b> I joined the Computing Infrastructure Group at The University of Oxford as a postdoctoral researcher.</li>
<li><b>[Jan 2025]</b> After 3 years and 10 months, my research journey at IMDEA Networks Institute finally ended on 31 January 2025. I am grateful for the strong research foundation I gained over the years.</li>
<li><b>[Jan 2025]</b> Our paper "Real-Time Encrypted Traffic Classification in Programmable Networks with P4 and Machine Learning" has been published in Wiley's <i>International Journal of Network Management</i>. This work builds on and extends our previous IEEE/IFIP NOMS 2024 paper which was joint work with Orange Labs in France.</li>
<li><b>[Oct 2024]</b> I attended IEEE ICNP in Charleroi, Belgium, where I presented our accepted paper at the 7th European P4 Workshop.</li>
<li><b>[Sep 2024]</b> Our paper "Towards Real-Time Intrusion Detection in P4-Programmable 5G User Plane Functions" has been accepted at the Euro'P4 workshop co-located with IEEE ICNP which will be held in Charleroi, Belgium, 28-31 October 2024.</li>
<li><b>[July 2024]</b> I have been invited to the PAM 2025 Program Committee.</li>
<li><b>[June 2024]</b> I have been accepted to serve on the SIGCOMM 2024 Artifact Evaluation Committee.</li>
<li><b>[June 2024]</b> I attended ACM e-Energy in Singapore, 4-7 June 2024.</li>
<li><b>[May 2024]</b> I attended IEEE INFOCOM, Vancouver, Canada, 20-23 May 2024.</li>
<li>🏆 <b>[May 2024]</b> I attended IEEE/IFIP NOMS in Seoul, South Korea, 6-10 May 2024. I also got awarded an <strong>IEEE ComSoc Student Travel Grant</strong>.</li>
<li><b>[May 2024]</b> I completed my 8-month secondment in Cambridge, United Kingdom and returned to Madrid.</li>
<li>🏆 <b>[Apr 2024]</b> I was awarded an <strong>ACM SIGEnergy Student Travel Grant</strong>.</li>
<li><b>[Apr 2024]</b> Our paper "Ultra-Low Latency User-Plane Cyberattack Detection in SDN-based Smart Grids" has been accepted at the ACM EnergySP'24 workshop co-located with ACM e-Energy'24 which will be held in Singapore, 4-7 June 2024.</li>
<li><b>[Mar 2024]</b> Our paper "Towards Data-Driven Management of Mobile Networks through User Plane Inference" has been accepted at the NOMS 2024 Doctoral Symposium to be held in Seoul, South Korea, 6-10 May 2024.</li>
<li><b>[Feb 2024]</b> Our paper "Evaluating the Impact of Flow Length on the Performance of In-Switch Inference Solution" has been accepted at the Computer and Networking Experimental Research using Testbeds Workshop (CNERT 2024), co-located with IEEE INFOCOM 2024 in Vancouver.</li>
<li><b>[Jan 2024]</b> I attended the BANYAN project final meeting in Uppsala, Sweden from 25-26 January.</li>
<li><b>[Dec 2023]</b> Our paper "Encrypted Traffic Classification at Line Rate in Programmable Switches with Machine Learning" has been accepted at NOMS 2024 - IEEE/IFIP Network Operations and Management Symposium, Seoul, South Korea, 6-10 May 2024.</li>
<li><b>[Dec 2023]</b> Our paper "Jewel: Resource-Efficient Joint Packet and Flow Level Inference in Programmable Switches" has been accepted at IEEE INFOCOM 2024 - IEEE Conference on Computer Communications, Vancouver, Canada, 20-23 May 2024.</li>
<li><b>[Sep 2023]</b> I started a 6-month research visit to the Department of Computer Science and Technology at the University of Cambridge in the UK.</li>
<li><b>[Sep 2023]</b> I started an 8-month research visit to Ranplan Wireless, Cambridge, UK.</li>
<li>🏆 <b>[June 2023]</b> Our demo, "Showcasing In-Switch Machine Learning Inference" won the <strong>Best Demo Award</strong> at IEEE NetSoft 2023 in Madrid, Spain.</li>
<li><b>[May 2023]</b> I attended IEEE INFOCOM 2023 in New York, USA from 17-20 May and presented our paper "Flowrest".</li>
<li><b>[Mar 2023]</b> I started a 6-month research visit to the SMART research team at Orange Labs, Paris, France.</li>
<li><b>[Feb 2023]</b> Our demo of the Flowrest paper was accepted to the IEEE INFOCOM 2023 Demo Session.</li>
<li><b>[Dec 2022]</b> I attended ACM CoNEXT 2022 in Rome, Italy from 5-10 December and presented our paper "Henna" at the 1st International Workshop on Native Network Intelligence (NATIVENI).</li>
<li><b>[Dec 2022]</b> Our paper "Flowrest: Practical Flow-Level Inference in Programmable Switches with Random Forests" has been accepted at IEEE INFOCOM 2023 - IEEE Conference on Computer Communications, New York, USA, 17-20 May 2023.</li>
<li><b>[Nov 2022]</b> Our paper "Henna: Hierarchical Machine Learning Inference in Programmable Switches" was accepted at the The 1st International Workshop on Native Network Intelligence Co-located with ACM CoNEXT 2022 in Rome, Italy, 5-10 December 2022.</li>
<li><b>[Oct 2022]</b> I started a 4-month research to the Department of Computer Science and Technology at the University of Cambridge in the UK.</li>
</ul>
</div>
