This file is a merged representation of the entire codebase, combined into a single document by Repomix.

# File Summary

## Purpose
This file contains a packed representation of the entire repository's contents.
It is designed to be easily consumable by AI systems for analysis, code review,
or other automated processes.

## File Format
The content is organized as follows:
1. This summary section
2. Repository information
3. Directory structure
4. Repository files (if enabled)
5. Multiple file entries, each consisting of:
  a. A header with the file path (## File: path/to/file)
  b. The full contents of the file in a code block

## Usage Guidelines
- This file should be treated as read-only. Any changes should be made to the
  original repository files, not this packed version.
- When processing this file, use the file path to distinguish
  between different files in the repository.
- Be aware that this file may contain sensitive information. Handle it with
  the same level of security as you would the original repository.

## Notes
- Some files may have been excluded based on .gitignore rules and Repomix's configuration
- Binary files are not included in this packed representation. Please refer to the Repository Structure section for a complete list of file paths, including binary files
- Files matching patterns in .gitignore are excluded
- Files matching default ignore patterns are excluded
- Files are sorted by Git change count (files with more changes are at the bottom)

# Directory Structure
```
cv.pdf
index.html
README.md
style.css
```

# Files

## File: style.css
```css
/* style.css */

/* ---------- Reset / Base ---------- */
body {
  margin: 0;
  padding: 0;
  background-color: #f0f0f0;
  font-family: Verdana, Geneva, Arial, sans-serif;
  font-size: 12px;
  color: #333;
  line-height: 1.5;
}

a {
  color: #0000cc;
  text-decoration: underline;
}

a:visited {
  color: #551a8b;
}

a:hover {
  color: #cc0000;
}

h1, h2, h3 {
  font-family: Arial, Helvetica, sans-serif;
  font-weight: bold;
  color: #333;
}

p {
  margin: 0 0 10px 0;
}

/* ---------- Container ---------- */
#container {
  width: 760px;
  margin: 15px auto;
  background-color: #ffffff;
  border: 1px solid #999999;
}

/* ---------- Header ---------- */
#header {
  background-color: #e8e8e8;
  border-bottom: 1px solid #999999;
  padding: 15px 20px 10px 20px;
}

#header h1 {
  margin: 0;
  font-size: 26px;
  letter-spacing: 1px;
}

#header .tagline {
  margin: 3px 0 0 0;
  font-size: 11px;
  color: #666666;
  font-style: italic;
}

/* ---------- Navigation ---------- */
#nav {
  background-color: #dddddd;
  border-bottom: 1px solid #999999;
  padding: 5px 20px;
}

#nav ul {
  margin: 0;
  padding: 0;
  list-style: none;
}

#nav li {
  display: inline;
  margin-right: 5px;
  padding-right: 5px;
  border-right: 1px solid #999999;
}

#nav li:last-child {
  border-right: none;
}

#nav a {
  font-size: 12px;
  font-weight: bold;
  color: #0000cc;
  text-decoration: none;
  padding: 0 2px;
}

#nav a:hover {
  text-decoration: underline;
  color: #cc0000;
}

/* ---------- Main / Sections ---------- */
#main {
  padding: 20px;
  overflow: hidden; /* clearfix */
}

.section {
  margin-bottom: 30px;
}

.section h2 {
  font-size: 18px;
  border-bottom: 1px dashed #cccccc;
  padding-bottom: 4px;
  margin: 0 0 12px 0;
}

/* ---------- Home / Intro ---------- */
.intro {
  overflow: hidden;
}

.avatar {
  float: left;
  width: 190px;
  height: 190px;
  background-color: #e6eef5;
  border: 1px solid #999999;
  margin: 0 15px 10px 0;
  text-align: center;
  font-size: 28px;
  font-weight: bold;
  color: #555555;
  line-height: 90px;
  font-family: Arial, Helvetica, sans-serif;
}

.intro p {
  margin-top: 0;
  font-size: 13px;
}

/* ---------- CV ---------- */
.cvbox {
  background-color: #fafafa;
  border: 1px solid #cccccc;
  padding: 12px;
}

.cvbox p {
  font-size: 12px;
}

.button {
  display: inline-block;
  padding: 3px 10px;
  background-color: #e8e8e8;
  border: 1px solid #999999;
  border-right-color: #666666;
  border-bottom-color: #666666;
  color: #000000;
  text-decoration: none;
  font-size: 12px;
  font-family: Verdana, Geneva, Arial, sans-serif;
  cursor: pointer;
}

.button:hover {
  background-color: #d8d8d8;
  color: #000000;
}

/* ---------- Social ---------- */
.social-list {
  margin: 0;
  padding: 0;
  list-style: none;
}

.social-list li {
  display: inline;
  margin-right: 5px;
  padding-right: 5px;
  border-right: 1px solid #cccccc;
}

.social-list li:last-child {
  border-right: none;
}

.social-list a {
  font-size: 12px;
}

/* ---------- Blog ---------- */
.post {
  background-color: #f9f9f9;
  border: 1px solid #cccccc;
  padding: 10px;
  margin-bottom: 15px;
}

.post .date {
  font-size: 11px;
  color: #666666;
  font-style: italic;
  margin-bottom: 3px;
}

.post h3 {
  font-size: 14px;
  margin: 0 0 6px 0;
}

.post p {
  font-size: 12px;
  margin-bottom: 6px;
}

.post a {
  font-size: 12px;
}

/* ---------- Footer ---------- */
#footer {
  border-top: 1px solid #cccccc;
  background-color: #f4f4f4;
  padding: 10px 20px;
  text-align: center;
  font-size: 11px;
  color: #666666;
}

#footer p {
  margin: 3px 0;
}
```

## File: index.html
```html
<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Martin Lau's webpage</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <div id="container">

    <!-- ============ HEADER ============ -->
    <div id="header">
      <h1>Martin Lau</h1>
      <p class="tagline">M2 Data Science Student at X-HEC</p>
    </div>

    <!-- ============ NAVIGATION ============ -->
    <div id="nav">
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#cv">CV</a></li>
        <li><a href="#social">Social</a></li>
        <li><a href="#blog">Blog</a></li>
      </ul>
    </div>

    <!-- ============ MAIN CONTENT ============ -->
    <div id="main">

      <!-- HOME / INTRO -->
      <div id="home" class="section">
        <h2>Welcome</h2>
        <div class="intro">
          <div class="avatar">JD</div>
          <p>
            Hello hello, welcome to my webpage! I come from Hong Kong, and am currently living in France.
          </p>
          <p>
            Below you'll find a couple snippets of my life.
          </p>
        </div>
      </div>

      <!-- CV -->
      <div id="cv" class="section">
        <h2>CV</h2>
        <div class="cvbox">
          <p>
            If you're interested in my profile and my skills, please feel free to contact me
          </p>
          <p><a href="cv.pdf" class="button" target="_blank" rel="noopener">Download CV (PDF)</a></p>
        </div>
      </div>

      <!-- SOCIAL -->
      <div id="social" class="section">
        <h2>Find Me Online</h2>
        <ul class="social-list">
          <li><a href="https://linkedin.com/in/-martinlau" target="_blank" rel="noopener">LinkedIn</a></li>
          <li><a href="https://github.com/thatmartinlau" target="_blank" rel="noopener">GitHub</a></li>
          <li><a href="mailto:thatmartinlau@gmail.com">Email</a></li>
        </ul>
      </div>

      <!-- BLOG -->
      <div id="blog" class="section">
        <h2>From the Blog</h2>

        <div class="post">
          <p class="date">March 2025</p>
          <h3>Designing with a pale palette</h3>
          <p>
            Why soft, low-contrast colours can still be accessible — and how
            to get the details right.
          </p>
          <p><a href="#">Read more &raquo;</a></p>
        </div>

        <div class="post">
          <p class="date">February 2025</p>
          <h3>A small CSS reset I keep reusing</h3>
          <p>
            Six lines that save me from browser inconsistencies on every
            new project.
          </p>
          <p><a href="#">Read more &raquo;</a></p>
        </div>

        <div class="post">
          <p class="date">January 2025</p>
          <h3>Notes from a slow January</h3>
          <p>
            On gardening, reading, and the quiet value of doing less for a
            little while.
          </p>
          <p><a href="#">Read more &raquo;</a></p>
        </div>

      </div>

    </div><!-- /main -->

    <!-- ============ FOOTER ============ -->
    <div id="footer">
      <p>&copy; 2025 Jamie Doe. All rights reserved.</p>
      <p>Last updated: 4 November 2026</p>
      <p>My contacts:
      <a href="cv.pdf" target="_blank" rel="noopener">CV</a>
      <a href="https://linkedin.com/in/-martinlau" target="_blank" rel="noopener">LinkedIn</a>
      <a href="https://github.com/thatmartinlau" target="_blank" rel="noopener">GitHub</a>
      <a href="mailto:thatmartinlau@gmail.com">Email</a>
      </p>
    </div>

  </div><!-- /container -->

</body>
</html>
```

## File: README.md
```markdown

```
