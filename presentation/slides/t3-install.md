<!-- .slide: data-breadcrumb="Installation VS Duplication" -->
# First step :

<table class="reveal">
  <thead>
    <tr>
      <th width="48%"><img src="img/ico_install.png" width="50" alt=""/> Installation</th>
      <th width="4%" class="vs">VS</th>
      <th width="48%"><img src="img/ico_clone.png" width="50" alt=""/> Duplication</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <ul class="fragment fade-in">
          <li>3-5 steps for dummies</li>
          <li>Package inclusion</li>
        </ul>
      </td>
      <td></td>
      <td>
        <ul class="fragment fade-in">
          <li>2 questions (username, name of the project)</li>
          <li>Configuration for common extensions</li>
          <li>Common typoscript configuration (menus, logo, favicon, ...)</li>
          <li>Project spread on multiple environments</li>
          <li>Server configuration, versioning, local files, ...</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

<img src="img/demo-install.gif" alt="" class="fragment fade-in"/>

note:
  First step: Should I install a new instance or duplicate an existing one ?<br />
  What makes a installation? cf. slide<br />
  Since many years pre-installed frameworks florish. You've certainly heard of Twitter bootstrap, Introduction package, Government package... For us, they are wonderfull tools... to make quick demo, but not to start Agency's projects. Why?<br />
  The answer is pretty simple. They includes too many futile things! When I start a project, I don't want to remove demo pages, I don't want to clean 2000 lines of CSS. I want to build things. A developer is a creator, not a cleaner. (don't make me say what I didn't say: I love maids :p)<br />
  Maybe, we could make a Inouit package with our typo3 configuration but our needs exceed typo3 boundaries so we have a typo3 almost empty installation (easy to maintain) that we duplicate with a script. What are the differences? cf. slide