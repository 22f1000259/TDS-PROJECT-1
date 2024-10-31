# TDS-PROJECT-1
Repository for IITM TDS Project 1

 ## GitHub Users in Austin

This repository contains data about GitHub users in Austin with over 100 followers and their repositories.

## Files

1. `users.csv`: Contains information about 476 GitHub users in Austin with over 100 followers
2. `repositories.csv`: Contains information about 41311 public repositories from these users
3. `github_scraper.py`: Python script used to collect this data

<!DOCTYPE html>
<html lang="en">

<body>

<h1>Austin GitHub Community Insights</h1>

<h2>🚀 Top Programming Languages</h2>
<ul>
    <li><strong>JavaScript</strong>: 9,033 repositories</li>
    <li><strong>Python</strong>: 3,665 repositories</li>
    <li><strong>Ruby</strong>: 2,455 repositories</li>
    <li><strong>Go</strong>: 1,661 repositories</li>
    <li><strong>TypeScript</strong>: 1,565 repositories</li>
</ul>

<h2>🌟 Most Starred Repository</h2>
<p>
    The most popular repository is <strong>"getify/You-Dont-Know-JS"</strong> with 
    <strong>179,606 stars</strong> and an equal number of watchers. Created by 
    <strong>getify</strong>, this repository showcases exceptional popularity and community impact.
</p>

<h2>👤 Top Users by Repository Count</h2>
<table border="1" cellpadding="8" cellspacing="0">
    <thead>
        <tr>
            <th>User</th>
            <th>Repositories</th>
            <th>Followers</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>steveklabnik</td>
            <td>832</td>
            <td>6,802</td>
        </tr>
        <tr>
            <td>FellowTraveler</td>
            <td>638</td>
            <td>206</td>
        </tr>
        <tr>
            <td>PaulBratslavsky</td>
            <td>574</td>
            <td>197</td>
        </tr>
        <tr>
            <td>schneems</td>
            <td>481</td>
            <td>2,437</td>
        </tr>
        <tr>
            <td>cloudflare</td>
            <td>475</td>
            <td>6,440</td>
        </tr>
    </tbody>
</table>

<h2>📊 Follower Distribution Among Austin-based Users</h2>
<p>
    Austin-based users show a wide range of influence, with an <strong>average of 548 followers</strong>. 
    The most-followed user has an impressive <strong>43,934 followers</strong>, reflecting a vibrant 
    local community of developers.
</p>

</body>
</html>


## Data Collection

- Data collected using GitHub API
- Date of collection: 2024-10-31
- Only included users with 100+ followers
- Up to 500 most recently pushed repositories per user
