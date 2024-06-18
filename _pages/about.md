---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div class="bio-block">
  <p>
    <strong>Dipanjyoti Paul</strong> is an Assistant Professor in the Department of Computer Science at the Institute of Systems and Information Engineering, University of Tsukuba, Japan. He is also a member of the Center for Artificial Intelligence Research (C-AIR). Additionally, he holds an affiliation as a Visiting Scientist in the Department of Computer Science & Engineering at The Ohio State University, USA. Previously, he served as a postdoctoral fellow at the Imageomics Institute within the Department of Computer Science & Engineering at The Ohio State University, USA. Dipanjyoti Paul earned his Ph.D. from the Department of Computer Science & Engineering at the Indian Institute of Technology Patna, India. Dipanjyoti Paul's research spans various domains, focusing on the intersection of biology and machine learning, explainable AI, computer vision, streaming data, real-time summarization, among others. He has contributed to numerous journals and conferences, including ICLR, Knowledge-Based Systems, Pattern Recognition, Expert Systems with Applications, IEEE Transactions on Computational Social Systems, Pattern Recognition Letters, ACM Transactions on Knowledge Discovery from Data, and more.
  </p>
</div>
<style>
.bio-block {
  border: 1px solid #ddd;
  padding: 20px;
  margin: 20px 0 10px; /* Reduced bottom margin */
  border-radius: 5px;
  background-color: #f9f9f9;
  font-family: 'Times New Roman', Times, serif; /* Change the font family here */
}
.bio-block p {
  margin: 0;
  line-height: 1.6;
}
.bio-block strong {
  color: #007bff; /* Optional: customize the color */
}
</style>
<div class="download-section">
    <button id="download-cv" class="download-btn">Download CV</button>
</div>
<style>
.download-section {
    text-align: center;
    margin-top: 10px; /* Reduced top margin */
}
.download-btn {
    padding: 10px 20px;
    font-size: 16px;
    color: white;
    background-color: #007BFF;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s;
}
.download-btn:hover {
    background-color: #0056b3;
}
</style>
<script>
document.getElementById('download-cv').addEventListener('click', function() {
    // Replace 'cv.pdf' with the path to your actual CV file
    const cvFilePath = '../files/Dr_Dipanjyoti_Paul_CV.pdf';

    const link = document.createElement('a');
    link.href = cvFilePath;
    link.download = 'Dr_Dipanjyoti_Paul_CV.pdf'; // This will be the name of the downloaded file
    document.body.appendChild(link);
    link.click();
    document.body.removeChild(link);
});
</script>

<div class="recent-news" style="background-color: #f8d7da; padding: 20px; border-radius: 5px; margin-bottom: 20px; margin-top: 10px;">
  <h2 class="recent-news-heading" style="color: #dc3545; font-size: 24px; margin-top: 0;">Recent News</h2>
  <ul class="recent-news-list" style="list-style-type: disc; padding-left: 20px;">
    <li>Attended the ICLR-24 conference in Vienna, Austria, and presented a paper.</li>
    <li>Our paper INterpretable TRansformer has been accepted at the ICLR-24 conference.</li>
    <li>Our paper INterpretable TRansformer has been accepted for presentation at the CVPR-24 workshop, CV4Animals, in Seattle, USA.</li>
  </ul>
</div>
