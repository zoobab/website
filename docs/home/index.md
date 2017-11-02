---
approvers:
- chenopis
title: Kubernetes Documentation
layout: docsportal
cid: userJourneys
css: /css/style_user_journeys.css
js: /js/user-journeys.js, https://use.fontawesome.com/4bcc658a89.js
---

{% unless page.notitle %}
<h1>{{ page.title }}</h1>
{% endunless %}

<div class="bar1">
    <div class="navButton users" onClick="showOnlyDocs(false)">Users</div>
    <div class="navButton contributors" onClick="showOnlyDocs(false)">Contributors</div>
    <div class="navButton migrators" onClick="showOnlyDocs(false)">Migration&nbsp;Paths</div>
    <a href="#" onClick="showOnlyDocs(true)"> <div class="navButton">Browse Docs</div></a>
</div>

<div id="cardWrapper">
  <div class="bar2">I AM...</div>
  <div class='cards'></div>
</div>

<div style='text-align: center;' class="applicationDeveloperContainer">
    <div class="bar2" id="subTitle">LEVEL</div>
    <div class="bar3">
        <div class="tab1 foundational" id="beginner">
            <i class="fa fa-cloud-download" aria-hidden="true" style="font-size:50pt !important;padding-top:7% !important;padding-bottom:15% !important"></i>
            <br>
            <div class="tabbottom" style="padding-top:5%;padding-bottom:5%">
                Foundational
            </div>
            </div>
        <div class="tab1 intermediate">
            <i class="fa fa-check-square" aria-hidden="true" style="font-size:50pt !important;padding-top:7% !important;padding-bottom:15% !important"></i>
            <br>

            <div class="tabbottom" style="padding-top:5%;padding-bottom:5%">
                Intermediate
            </div>
        </div>
        <div class="tab1 advanced">
            <i class="fa fa-exclamation-circle" aria-hidden="true" style="font-size:50pt !important;padding-top:7% !important;padding-bottom:15% !important"></i>
            <br>
            <div class="tabbottom" style="padding-top:5%;padding-bottom:5%">
                Advanced Topics
            </div>
        </div>
      </div>
</div>

<div class='infobarWrapper'>
    <div class="infobar">
        <span style="padding-bottom: 3% ">I want to...</span>
        <a id="infolink1" href="docs.html"><div class="whitebar" >
            <div class="infoicon">
                <i class="fa fa-folder-open-o" aria-hidden="true" style="padding:%;float:left;color:#3399ff"></i>
            </div>
            <div id="info1" class='data'></div>
        </div></a>
        <a id="infolink2" href="docs.html"><div class="whitebar">
            <div class="infoicon">
                <i class="fa fa-retweet" aria-hidden="true" style="padding-bottom:%;float:left;color:#3399ff"></i>
            </div>
            <div id="info2" class='data'></div>
        </div></a>
        <a id="infolink3" href="docs.html"> <div class="whitebar">
            <div class="infoicon">
                <i class="fa fa-hdd-o" aria-hidden="true" style="padding:%;float:left;color:#3399ff;margin-right:9px"></i>
            </div>
            <div id="info3" class='data'></div>
        </div></a>
    </div>
</div>


  <div class="browseheader" id="browsedocs">
      <a name="browsedocs">  Browse Docs</a>
      </div>
    
<div class="browsedocs">

<div class="browsesection">

        <div class="docstitle">
          <a href="#">Setup</a>
        </div>

        <div class="pages">
            <div class="browsecolumn">

            <a href="#" >01 - Picking the Right Solution</a><br>
            <a href="#" >02 - Independent Solutions</a><br>
          </div>
          <div class="browsecolumn">
            <a href="#" >03 - Hosted Solutions</a><br>
            <a href="#" >04 - Turn-key Cloud Solutions</a><br>
            </div>
            <div class="browsecolumn">
            <a href="#" >05 - Custom Solutions</a><br>
          </div>


        </div>

  </div>

  <div class="browsesection">

        <div class="docstitle">
          <a href="#">Concepts</a>
        </div>

        <div class="pages">
          <div class="browsecolumn">
            <a href="#" >01 - Overview</a><br>
            <a href="#" >02 - Kubernetes Architecture</a><br>
            <a href="#" >03 - Extending the Kubernetes API</a><br>
          </div>
            <div class="browsecolumn">
            <a href="#" >04 - Containers</a><br>
            <a href="#" >05 - Workloads</a><br>

            <a href="#" >06 - Configuration</a><br>
          </div>
            <div class="browsecolumn">
            <a href="#" >07 - Services, Load Balancing, and Networking</a><br>
            <a href="#" >08 - Storage</a><br>
            <a href="#" >09 - Cluster Administration</a><br>
          </div>
        </div>
</div>

<div class="browsesection">
        <div class="docstitle">
          <a href="#">Tasks</a>
        </div>

        <div class="pages">
              <div class="browsecolumn">
            <a href="#" >01 - Install Tools</a><br>
            <a href="#" >02 - Configure Pods and Containers</a><br>
            <a href="#" >03 - Inject Data Into Applications</a><br>
            <a href="#" >04 - Run Applications</a><br>
            <a href="#" >05 - Run Jobs</a><br>
          </div>
              <div class="browsecolumn">
            <a href="#" >06 - Access Applications in a Cluster</a><br>
            <a href="#" >07 - Monitor, Log, and Debug</a><br>
            <a href="#" >08 - Access and Extend the Kubernetes API</a><br>
            <a href="#" >09 - TLS</a><br>
            <a href="#" >10 - Administer a Cluster</a><br>
          </div>
              <div class="browsecolumn">
            <a href="#" >11 - Federation - Run an App on Multiple Clusters</a><br>
            <a href="#" >12 - Manage Cluster Daemons</a><br>
            <a href="#" >13 - Manage GPUs</a><br>
            <a href="#" >14 - Manage HugePages</a><br>
            <a href="#" >15 - Extend kubectl with plugins</a><br>
          </div>
        </div>

</div>
<div class="browsesection">
        <div class="docstitle">
          <a href="#">Tutorials</a>
        </div>

        <div class="pages">
          <div class="browsecolumn">
            <a href="#" >01 - Kubernetes Basics</a><br>
            <a href="#" >02 - Online Training Courses</a><br>
            <a href="#" >03 - Configuration</a><br>
          </div>
          <div class="browsecolumn">
            <a href="#" >04 - Object Management Using kubectl</a><br>

            <a href="#" >05 - Stateless Applications</a><br>
            <a href="#" >06 - Stateful Applications</a><br>
          </div>
          <div class="browsecolumn">
            <a href="#" >07 - Clusters</a><br>
            <a href="#" >08 - Services</a><br>
          </div>
        </div>
</div>

<div class="browsesection">

        <div class="docstitle">
          <a href="#">Reference</a>
        </div>

        <div class="pages">
          <div class="browsecolumn">
            <a href="#" >01 - Using the API</a><br>
            <a href="#" >02 - API Reference</a><br>
            <a href="#" >03 - Federation API</a><br>
          </div>
              <div class="browsecolumn">
            <a href="#" >04 - kubectl CLI</a><br>
            <a href="#" >05 - Cloud Controller Manager</a><br>
            <a href="#" >06 - Setup Tools</a><br>
          </div>
              <div class="browsecolumn">
            <a href="#" >07 - Config Reference</a><br>
            <a href="#" >08 - Kubernetes Design Docs</a><br>
            <a href="#" >09 - Kubernetes Issues and Security</a><br>
          </div>
            <br><br><br><br><br>
        </div>
    </div>
</div>
