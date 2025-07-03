---
layout: default
title: "The Microbial Biosignatures Project: About"
permalink: /about/
---

<h1>About the Project</h1>

<p>
  This project began as a Microsoft Access database to organize and
  track field locations, images, geochemical data, and other aspects of
  microbialite samples collected by
  <a href="{{ '/team/' | relative_url }}">Hickson and Bartley</a>.
  As this resource grew, we realized that an open-source database for the scientific community
  could be used to answer important
  <a href="{{ '/science/' | relative_url }}">scientific questions</a> about early life on
  Earth, life on other planets, evolution, and interpretations of
  paleoecology in the rock record.
</p>

<p>
  At the same time, it became clear that microbialite sedimentologists
  lacked a common, non-genetic, descriptive vocabulary for these
  important sedimentary features. That is until 2020, when Stan Awramik
  and Kath Grey published their
  <a
    href="https://www.dmp.wa.gov.au/Geological-Survey/Handbook-for-the-study-and-26950.aspx"
    >Handbook for the Study of Microbialites</a
  >. This free, online text provided an ideal starting point for the
  creation of a controlled vocabulary that geologists could use to
  describe a wide range of microbialites. We fully integrated their
  descriptive scheme into our database. It was at this point that we
  began to consider developing an open-source version for the geoscience
  community.
</p>

<h2>What we have done, where we're going</h2>

<table class="pure-table pure-table-bordered">
  <thead>
    <tr>
      <th>Task(s)</th>
      <th>Status</th>
    </tr>
  </thead>
  <tbody>
    <tr class="pure-table-odd">
      <td>
        Develop a prototype MS Access database that incorporates Awramik
        and Grey's (2020) classification into the description of
        microbialites from field localities and the literature.
      </td>
      <td>COMPLETE</td>
    </tr>
    <tr>
      <td>
        Database back-end: migrate prototype MS Access schema and tables
        to PostgreSQL, an open-source relational database format
      </td>
      <td>COMPLETE</td>
    </tr>
    <tr class="pure-table-odd">
      <td>
        Database front-end: convert prototype MS Access forms and
        queries to use the PostgreSQL back-end. At this point we are
        keeping the front-end development in MS Access to allow the
        non-computer science team members to contribute. This will later
        be replaced by a web-based (React) front-end. Many of the
        pass-through queries created in this stage will transfer to
        Javascript-based code later.
      </td>
      <td>COMPLETE</td>
    </tr>
    <tr>
      <td>
        Migrate back-end to Jetstream2 cloud server. Link MS Access
        front-end to this back-end and test.
      </td>
      <td>COMPLETE</td>
    </tr>
    <tr class="pure-table-odd">
      <td>
        Share MS Access front-end with small user group to get feedback
        on the database. What is working? What needs improvement? What
        features are missing?
      </td>
      <td>IN PROGRESS</td>
    </tr>
    <tr>
      <td>
        Begin development of Javascript and React front-end with
        computer science team members and undergraduate computer science
        students.
      </td>
      <td>Summer 2025</td>
    </tr>
    <tr class="pure-table-odd">
      <td>
        Submit NASA and/or NSF proposals to support further development,
        integration with other paleobiology databases (API development),
        and improvements to schema and front-end.
      </td>
      <td>September 2025</td>
    </tr>
    <tr>
      <td>
        Workshop at Microbialites: Formation, Evolution, Diagenesis (M-FED) 2025 Conference, Hannover, Germany: <i>A Listening Session on the Development of an Open-Source Microbialites Database</i>
      </td>
      <td>Early October 2025</td>
    </tr>
    <tr class="pure-table-odd">
      <td>
        Workshop at GSA Connects, San Antonio <i>An Open-Source Microbialites Database for the Geoscience Community: Mini-workshop and Listening Session</i>
      </td>
      <td>Late October 2025</td>
    </tr>
    <tr>
      <td>
        Share initial database with scientific community at the
        Geological Society of American National Meeting to get feedback
        and encourage participation.
      </td>
      <td>October 2025</td>
    </tr>
    <tr class="pure-table-odd">
      <td>
        Integrate comments from community and develop working PostgreSQL
        backend with dynamic, web-based front-end.
      </td>
      <td>Spring and Summer, 2026</td>
    </tr>
  </tbody>
</table>

<h1>Funding and Other Support</h1>

<p>To date this work has been supported by the:</p>
<ul>
  <li>
    The National Science Foundation's <a href = "https://access-ci.org/">Access Ecosystem</a> and <a href = "https://docs.jetstream-cloud.org/">JetStream2</a> cloud computing resources for scientists
  </li>
  <li>
    University of St. Thomas Department of Earth, Environment, and
    Society and the Undergraduate Research Opportunities (UROP) program
  </li>
  <li>
    Gustavus Adolphus College, Environment, Geography, and Earth
    Sciences
  </li>
</ul>
