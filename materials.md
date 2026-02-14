---
layout: page
title: Materials
permalink: /materials/
---

<style>
.materials-container {
    max-width: 800px;
    margin: 0 auto;
}
.section-title {
    border-bottom: 2px solid #007bff;
    padding-bottom: 5px;
    margin-top: 30px;
    color: #333;
}
.course-list {
    list-style: none;
    padding: 0;
}
.course-list li {
    margin-bottom: 12px;
    padding-left: 20px;
    border-left: 3px solid #007bff;
}
.course-list li a {
    font-weight: 500;
    text-decoration: none;
    color: #0056b3;
}
.course-list li a:hover {
    text-decoration: underline;
}
.course-list li small {
    display: block;
    color: #666;
    font-size: 0.9em;
    margin-top: 3px;
}
.resource-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 15px;
    margin-top: 15px;
}
.resource-card {
    background: #f8f9fa;
    padding: 12px;
    border-radius: 8px;
    text-align: center;
    transition: transform 0.2s;
}
.resource-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}
.resource-card a {
    text-decoration: none;
    color: #007bff;
    font-weight: 500;
}
.resource-card p {
    margin: 5px 0 0;
    font-size: 0.85em;
    color: #555;
}
.book-item {
    background: #f1f3f5;
    padding: 10px 15px;
    border-radius: 6px;
    margin: 10px 0;
}
</style>

<div class="materials-container">

{% include image.html url="/_images/screenshots/cover2.jpg" width=175 align="right" caption="Algorithm Design - Spring 2026" %}

## <i class="fas fa-book-open"></i> Textbook
**Algorithm Design - Spring 2026 - Dr. Eskandari**  
[📥 Download full textbook (PDF)](/static_files/presentations/algorithms_spring2026.pdf)  
<small>Direct download link (PDF, ~5 MB)</small>

---

## <i class="fas fa-university"></i> Similar Courses
<ul class="course-list">
  <li>
    <a href="https://web.stanford.edu/class/archive/cs/cs161/cs161.1138/" target="_blank">CS161 2013</a> – Stanford University
    <small>Classic algorithms course with lecture notes and assignments.</small>
  </li>
  <li>
    <a href="https://ocw.mit.edu/courses/6-046j-design-and-analysis-of-algorithms-spring-2015/" target="_blank">6.046J Design and Analysis of Algorithms (Spring 2015)</a> – MIT OpenCourseWare
    <small>Full video lectures, problem sets, and exams from Prof. Erik Demaine.</small>
  </li>
  <li>
    <a href="https://www.cs.cmu.edu/afs/cs/Web/People/15451/index.html" target="_blank">15-451/651: Algorithms</a> – Carnegie Mellon University
    <small>Advanced algorithms course; check Schedule section for materials.</small>
  </li>
  <li>
    <a href="https://student.cs.uwaterloo.ca/~cs341/" target="_blank">CS 341: Algorithms</a> – University of Waterloo
    <small>Winter 2026 offering with slides, assignments, and policy details.</small>
  </li>
  <li>
    <a href="https://www.cs.purdue.edu/homes/tamaldey/course/580/" target="_blank">CS 580: Algorithms</a> – Purdue University
    <small>Graduate-level algorithms by Prof. Tamal K. Dey.</small>
  </li>
  <li>
    <a href="https://www.cs.ox.ac.uk/teaching/courses/2021-2022/algdesign/" target="_blank">Design and Analysis of Algorithms (2021-2022)</a> – University of Oxford
    <small>16-lecture course with slides and problem sheets.</small>
  </li>
  <li>
    <a href="https://www.cs.princeton.edu/~wayne/kleinberg-tardos/" target="_blank">Algorithm Design (Kleinberg & Tardos) Lecture Slides</a> – Princeton University
    <small>Revised slides by Kevin Wayne accompanying the famous textbook.</small>
  </li>
  <li>
    <a href="https://www.cs.princeton.edu/~wayne/kleinberg-tardos/pearson/" target="_blank">Algorithm Design (Official Pearson Slides)</a> – Princeton University
    <small>Original publisher slides for instructors.</small>
  </li>
  <li>
    <a href="https://www.ebooksworld.ir/post/index/949" target="_blank">Grokking Algorithms (Illustrated Guide)</a> – EBooksWorld
    <small>Persian resource? Actually a book in English with visual explanations.</small>
  </li>
</ul>

---

## <i class="fas fa-star"></i> Recommended Books & References
<div class="book-item">
  <strong>📘 "Introduction to Algorithms"</strong> – Cormen, Leiserson, Rivest, Stein (CLRS)  
  <em>The definitive textbook for algorithm studies.</em>
</div>
<div class="book-item">
  <strong>📙 "Algorithm Design Manual"</strong> – Steven Skiena  
  <em>Practical advice and a catalog of algorithmic problems.</em>
</div>

### 🖥️ Online Judge Practice
<div class="resource-grid">
  <div class="resource-card">
    <a href="https://leetcode.com/" target="_blank">LeetCode</a>
    <p>Thousands of coding problems for interview prep.</p>
  </div>
  <div class="resource-card">
    <a href="https://www.hackerrank.com/" target="_blank">HackerRank</a>
    <p>Practice algorithms, data structures, and more.</p>
  </div>
</div>

<p><em>More resources will be added during the semester.</em></p>

---

## <i class="fas fa-link"></i> Additional Course Materials
<ul>
  <li><a href="https://docs.python.org/3/tutorial/" target="_blank">🐍 Python for Beginners</a> – Official Python tutorial (great for refresher).</li>
  <li><a href="https://visualgo.net" target="_blank">👁️ Visualgo</a> – Interactive visualizations of data structures and algorithms.</li>
  <li><a href="https://geeksforgeeks.org" target="_blank">📚 GeeksforGeeks</a> – Extensive collection of algorithm problems and explanations.</li>
</ul>

</div>
