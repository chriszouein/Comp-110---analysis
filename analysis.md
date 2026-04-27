---
layout: default
title: Analysis
---
<style>
body {
  background-color: #f7f9fc;
  color: #1f2937;
  font-family: Arial, sans-serif;
}

main, .container, .markdown-body {
  max-width: 900px;
  margin: auto;
  padding: 30px;
}

h1 {
  color: #1d4ed8;
  border-bottom: 3px solid #1d4ed8;
  padding-bottom: 10px;
}

h2 {
  color: #111827;
  margin-top: 35px;
}

h3 {
  color: #374151;
}

a {
  color: #2563eb;
  font-weight: bold;
}

img {
  max-width: 700px;
  width: 100%;
  border-radius: 10px;
  margin: 15px 0 30px 0;
  box-shadow: 0 4px 12px rgba(0,0,0,0.15);
}

hr {
  border: none;
  border-top: 2px solid #e5e7eb;
  margin: 30px 0;
}
</style>

# Analysis

## Step 1: Select Relevant Columns

We analyze whether students who find the course difficult, fast-paced, or hard to understand are more likely to want pre-lecture videos.

We load the survey data and focus on the following variables:
- pre-lecture videos  
- difficulty  
- pace  
- understanding  

---

## Step 2: Counting Response Frequencies

We compute the frequency of responses for each variable to understand how student answers are distributed.

This helps identify patterns before deeper analysis.

---

## Step 3: Difficulty vs Interest

We analyze how perceived difficulty relates to interest in pre-lecture videos.

![Difficulty vs Interest](graph1.png)

Students who report higher difficulty tend to show more interest in pre-lecture videos. However, even students with moderate difficulty still show interest, suggesting these videos benefit a wide range of students.

---

## Step 4: Pace vs Interest

We examine how course pace influences interest in pre-lecture videos.

![Pace vs Interest](graph2.png)

Students who perceive the course as faster-paced tend to have higher demand for pre-lecture videos. This suggests videos help students keep up with the material.

---

## Step 5: Understanding vs Interest

We investigate the relationship between understanding and interest in pre-lecture videos.

![Understanding vs Interest](graph3.png)

Students with lower levels of understanding show higher interest in pre-lecture videos. This indicates that these resources are especially useful for students who are struggling.

---

## Conclusion

Overall, students who perceive the course as more difficult, fast-paced, or harder to understand are more likely to want pre-lecture videos.

Pre-lecture videos can help students better prepare and improve their understanding, especially for those who need additional support.
