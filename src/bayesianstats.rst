
    

  

<!DOCTYPE html>
<html>
  <head>
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="chrome=1">
    <script type="text/javascript">var NREUMQ=[];NREUMQ.push(["mark","firstbyte",new Date().getTime()]);</script>
        <title>src/multivariateanalysis.rst at master from avrilcoghlan/LittleBookofRMultivariateAnalysis - GitHub</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub" />
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub" />

    
    

    <meta content="authenticity_token" name="csrf-param" />
<meta content="b0c9874007bc8e1776610fa3ee8573745b54e75d" name="csrf-token" />

    <link href="https://a248.e.akamai.net/assets.github.com/stylesheets/bundle_github.css?615dc4415914822f1692ffeb95691446f898bde0" media="screen" rel="stylesheet" type="text/css" />
    

    <script src="https://a248.e.akamai.net/assets.github.com/javascripts/jquery/jquery-1.6.1.min.js" type="text/javascript"></script>
    <script src="https://a248.e.akamai.net/assets.github.com/javascripts/bundle_github.js?f373938cafb20bd509faabe8e62f8a40298df4e1" type="text/javascript"></script>

    

    
  <link rel='permalink' href='/avrilcoghlan/LittleBookofRMultivariateAnalysis/blob/781a1ba06b3c4a367dc3e368cedce5a429954c76/src/multivariateanalysis.rst'>

  <link href="https://github.com/avrilcoghlan/LittleBookofRMultivariateAnalysis/commits/master.atom" rel="alternate" title="Recent Commits to LittleBookofRMultivariateAnalysis:master" type="application/atom+xml" />

    

    <meta name="description" content="LittleBookofRMultivariateAnalysis - Little Book of R for Multivariate Analysis" />
  

        <script type="text/javascript">
      var _gaq = _gaq || [];
      _gaq.push(['_setAccount', 'UA-3769691-2']);
      _gaq.push(['_setDomainName', 'none']);
      _gaq.push(['_trackPageview']);
      _gaq.push(['_trackPageLoadTime']);
      (function() {
        var ga = document.createElement('script');
        ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
        ga.setAttribute('async', 'true');
        document.documentElement.firstChild.appendChild(ga);
      })();
    </script>

  </head>

  

  <body class="logged_in page-blob  env-production">
    

    

    

    <div class="subnavd" id="main">
      <div id="header" class="true">
          <a class="logo boring" href="https://github.com/">
            
            <img alt="github" class="default" height="45" src="https://a248.e.akamai.net/assets.github.com/images/modules/header/logov6.png" />
            <!--[if (gt IE 8)|!(IE)]><!-->
            <img alt="github" class="hover" height="45" src="https://a248.e.akamai.net/assets.github.com/images/modules/header/logov6-hover.png" />
            <!--<![endif]-->
          </a>

        
          





  
    <div class="userbox">
      <div class="avatarname">
        <a href="https://github.com/avrilcoghlan"><img src="https://secure.gravatar.com/avatar/7e5b70fe19e67f2a228c8b82fc58d653?s=140&d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-140.png" alt="" width="20" height="20"  /></a>
        <a href="https://github.com/avrilcoghlan" class="name">avrilcoghlan</a>

        
        
          <a href="https://github.com/inbox/notifications" class="unread_count notifications_count new tooltipped downwards js-notification-count" title="Unread Notifications">1</a>
        
      </div>
      <ul class="usernav">
        <li><a href="https://github.com/">Dashboard</a></li>
        <li>
          
          <a href="https://github.com/inbox">Inbox</a>
          <a href="https://github.com/inbox" class="unread_count ">0</a>
        </li>
        <li><a href="https://github.com/account">Account Settings</a></li>
        <li><a href="/logout">Log Out</a></li>
      </ul>
    </div><!-- /.userbox -->
  


        
        <div class="topsearch">
  
    <form action="/search" id="top_search_form" method="get">
      <a href="/search" class="advanced-search tooltipped downwards" title="Advanced Search">Advanced Search</a>
      <div class="search placeholder-field js-placeholder-field">
        <label class="placeholder" for="global-search-field">Search…</label>
        <input type="text" class="search my_repos_autocompleter" id="global-search-field" name="q" results="5" /> <input type="submit" value="Search" class="button" />
      </div>
      <input type="hidden" name="type" value="Everything" />
      <input type="hidden" name="repo" value="" />
      <input type="hidden" name="langOverride" value="" />
      <input type="hidden" name="start_value" value="1" />
    </form>
    <ul class="nav">
      <li><a href="/explore">Explore GitHub</a></li>
      <li><a href="https://gist.github.com">Gist</a></li>
      
      <li><a href="/blog">Blog</a></li>
      
      <li><a href="http://help.github.com">Help</a></li>
    </ul>
  
</div>

      </div>

      
      
        
    <div class="site">
      <div class="pagehead repohead vis-public    instapaper_ignore readability-menu">

      

      <div class="title-actions-bar">
        <h1>
          <a href="/avrilcoghlan">avrilcoghlan</a> /
          <strong><a href="/avrilcoghlan/LittleBookofRMultivariateAnalysis" class="js-current-repository">LittleBookofRMultivariateAnalysis</a></strong>
          
          
        </h1>

        
    <ul class="actions">
      

      
        
          <li class="for-owner"><a href="/avrilcoghlan/LittleBookofRMultivariateAnalysis/admin" class="minibutton btn-admin "><span><span class="icon"></span>Admin</span></a></li>
        
        <li>
          
            <a href="/avrilcoghlan/LittleBookofRMultivariateAnalysis/toggle_watch" class="minibutton btn-watch unwatch-button" onclick="var f = document.createElement('form'); f.style.display = 'none'; this.parentNode.appendChild(f); f.method = 'POST'; f.action = this.href;var s = document.createElement('input'); s.setAttribute('type', 'hidden'); s.setAttribute('name', 'authenticity_token'); s.setAttribute('value', 'b0c9874007bc8e1776610fa3ee8573745b54e75d'); f.appendChild(s);f.submit();return false;"><span><span class="icon"></span>Unwatch</span></a>
          
        </li>
        
          
            <li><a href="/avrilcoghlan/LittleBookofRMultivariateAnalysis/fork" class="minibutton btn-fork fork-button" onclick="var f = document.createElement('form'); f.style.display = 'none'; this.parentNode.appendChild(f); f.method = 'POST'; f.action = this.href;var s = document.createElement('input'); s.setAttribute('type', 'hidden'); s.setAttribute('name', 'authenticity_token'); s.setAttribute('value', 'b0c9874007bc8e1776610fa3ee8573745b54e75d'); f.appendChild(s);f.submit();return false;"><span><span class="icon"></span>Fork</span></a></li>
          

          <li class='nspr'><a href="/avrilcoghlan/LittleBookofRMultivariateAnalysis/pull/new/master" class="minibutton btn-pull-request "><span><span class="icon"></span>Pull Request</span></a></li>
        
      
      
      <li class="repostats">
        <ul class="repo-stats">
          <li class="watchers watching">
            <a href="/avrilcoghlan/LittleBookofRMultivariateAnalysis/watchers" title="Watchers — You're Watching" class="tooltipped downwards">
              2
            </a>
          </li>
          <li class="forks">
            <a href="/avrilcoghlan/LittleBookofRMultivariateAnalysis/network" title="Forks - You have a fork" class="tooltipped downwards">
              1
            </a>
          </li>
        </ul>
      </li>
    </ul>

      </div>

        
  <ul class="tabs">
    <li><a href="/avrilcoghlan/LittleBookofRMultivariateAnalysis" class="selected" highlight="repo_source">Source</a></li>
    <li><a href="/avrilcoghlan/LittleBookofRMultivariateAnalysis/commits/master" highlight="repo_commits">Commits</a></li>
    <li><a href="/avrilcoghlan/LittleBookofRMultivariateAnalysis/network" highlight="repo_network">Network</a></li>
    <li><a href="/avrilcoghlan/LittleBookofRMultivariateAnalysis/pulls" highlight="repo_pulls">Pull Requests (0)</a></li>

    
      <li><a href="/avrilcoghlan/LittleBookofRMultivariateAnalysis/forkqueue" highlight="repo_fork_queue">Fork Queue</a></li>
    

    
      
      <li><a href="/avrilcoghlan/LittleBookofRMultivariateAnalysis/issues" highlight="issues">Issues (0)</a></li>
    

                <li><a href="/avrilcoghlan/LittleBookofRMultivariateAnalysis/wiki" highlight="repo_wiki">Wiki (0)</a></li>
        
    <li><a href="/avrilcoghlan/LittleBookofRMultivariateAnalysis/graphs" highlight="repo_graphs">Graphs</a></li>

    

    <li class="contextswitch nochoices">
      <span class="repo-tree toggle leftwards"
            
            data-master-branch="master"
            data-ref="master">
        <em>Branch:</em>
        <code>master</code>
      </span>
    </li>
  </ul>

  <div style="display:none" id="pl-description"><p><em class="placeholder">click here to add a description</em></p></div>
  <div style="display:none" id="pl-homepage"><p><em class="placeholder">click here to add a homepage</em></p></div>

  <div class="subnav-bar">
  
  <ul>
    <li>
      <a href="/avrilcoghlan/LittleBookofRMultivariateAnalysis/branches" class="dropdown">Switch Branches (1)</a>
      <ul class="subnav-dropdown-branches">
                              <li><strong>master &#x2713;</strong></li>
            
      </ul>
    </li>
    <li>
      <a href="#" class="dropdown defunct">Switch Tags (0)</a>
      
    </li>
    <li>
    
    <a href="/avrilcoghlan/LittleBookofRMultivariateAnalysis/branches" class="manage">Branch List</a>
    
    </li>
  </ul>
</div>

  
  
  
  
  
  



        
    <div id="repo_details" class="metabox clearfix">
      <div id="repo_details_loader" class="metabox-loader" style="display:none">Sending Request&hellip;</div>

      
        <a href="/avrilcoghlan/LittleBookofRMultivariateAnalysis/downloads" class="download-source" data-facebox-url="/avrilcoghlan/LittleBookofRMultivariateAnalysis/archives/master" id="download_button" title="Download source, tagged packages and binaries."><span class="icon"></span>Downloads</a>
      

      <div id="repository_desc_wrapper">
      <div id="repository_description" rel="repository_description_edit">
        
          <p>Little Book of R for Multivariate Analysis
            <span id="read_more" style="display:none">&mdash; <a href="#readme">Read more</a></span>
          </p>
        
      </div>

      <div id="repository_description_edit" style="display:none;" class="inline-edit">
        <form action="/avrilcoghlan/LittleBookofRMultivariateAnalysis/admin/update" method="post"><div style="margin:0;padding:0"><input name="authenticity_token" type="hidden" value="b0c9874007bc8e1776610fa3ee8573745b54e75d" /></div>
          <input type="hidden" name="field" value="repository_description">
          <input type="text" class="textfield" name="value" value="Little Book of R for Multivariate Analysis">
          <div class="form-actions">
            <button class="minibutton"><span>Save</span></button> &nbsp; <a href="#" class="cancel">Cancel</a>
          </div>
        </form>
      </div>

      
      <div class="repository-homepage" id="repository_homepage" rel="repository_homepage_edit">
        <p><a href="http://" rel="nofollow"></a></p>
      </div>

      <div id="repository_homepage_edit" style="display:none;" class="inline-edit">
        <form action="/avrilcoghlan/LittleBookofRMultivariateAnalysis/admin/update" method="post"><div style="margin:0;padding:0"><input name="authenticity_token" type="hidden" value="b0c9874007bc8e1776610fa3ee8573745b54e75d" /></div>
          <input type="hidden" name="field" value="repository_homepage">
          <input type="text" class="textfield" name="value" value="">
          <div class="form-actions">
            <button class="minibutton"><span>Save</span></button> &nbsp; <a href="#" class="cancel">Cancel</a>
          </div>
        </form>
      </div>
      </div>
      <div class="rule "></div>
      <div class="url-box">
  
    <ul class="native-clones">
      <li><a href="http://mac.github.com" class="minibutton btn-clone-in-mac "><span><span class="icon"></span> Clone in Mac</span></a></li>
    </ul>
  

  <ul class="clone-urls">
    
      
        <li class="private_clone_url"><a href="git@github.com:avrilcoghlan/LittleBookofRMultivariateAnalysis.git" data-permissions="Read+Write">SSH</a></li>
      
      <li class="http_clone_url"><a href="https://avrilcoghlan@github.com/avrilcoghlan/LittleBookofRMultivariateAnalysis.git" data-permissions="Read+Write">HTTP</a></li>
      <li class="public_clone_url"><a href="git://github.com/avrilcoghlan/LittleBookofRMultivariateAnalysis.git" data-permissions="Read-Only">Git Read-Only</a></li>
    
    
  </ul>
  <input type="text" spellcheck="false" class="url-field" />
        <span style="display:none" id="clippy_1562" class="url-box-clippy"></span>
      <span id="clippy_tooltip_clippy_1562" class="clippy-tooltip tooltipped" title="copy to clipboard">
      <object classid="clsid:d27cdb6e-ae6d-11cf-96b8-444553540000"
              width="14"
              height="14"
              class="clippy"
              id="clippy" >
      <param name="movie" value="https://a248.e.akamai.net/assets.github.com/flash/clippy.swf?v5"/>
      <param name="allowScriptAccess" value="always" />
      <param name="quality" value="high" />
      <param name="scale" value="noscale" />
      <param NAME="FlashVars" value="id=clippy_1562&amp;copied=&amp;copyto=">
      <param name="bgcolor" value="#FFFFFF">
      <param name="wmode" value="opaque">
      <embed src="https://a248.e.akamai.net/assets.github.com/flash/clippy.swf?v5"
             width="14"
             height="14"
             name="clippy"
             quality="high"
             allowScriptAccess="always"
             type="application/x-shockwave-flash"
             pluginspage="http://www.macromedia.com/go/getflashplayer"
             FlashVars="id=clippy_1562&amp;copied=&amp;copyto="
             bgcolor="#FFFFFF"
             wmode="opaque"
      />
      </object>
      </span>

  <p class="url-description"><strong>Read+Write</strong> access</p>
</div>

    </div>

    <div class="frame frame-center tree-finder" style="display:none" data-tree-list-url="/avrilcoghlan/LittleBookofRMultivariateAnalysis/tree-list/781a1ba06b3c4a367dc3e368cedce5a429954c76" data-blob-url-prefix="/avrilcoghlan/LittleBookofRMultivariateAnalysis/blob/781a1ba06b3c4a367dc3e368cedce5a429954c76">
      <div class="breadcrumb">
        <b><a href="/avrilcoghlan/LittleBookofRMultivariateAnalysis">LittleBookofRMultivariateAnalysis</a></b> /
        <input class="tree-finder-input" type="text" name="query" autocomplete="off" spellcheck="false">
      </div>

      
        <div class="octotip">
          <p>
            <a href="/avrilcoghlan/LittleBookofRMultivariateAnalysis/dismiss-tree-finder-help" class="dismiss js-dismiss-tree-list-help" title="Hide this notice forever">Dismiss</a>
            <strong>Octotip:</strong> You've activated the <em>file finder</em> by pressing <span class="kbd">t</span>
            Start typing to filter the file list. Use <span class="kbd badmono">↑</span> and <span class="kbd badmono">↓</span> to navigate,
            <span class="kbd">enter</span> to view files.
          </p>
        </div>
      

      <table class="tree-browser" cellpadding="0" cellspacing="0">
        <tr class="js-header"><th>&nbsp;</th><th>name</th></tr>
        <tr class="js-no-results no-results" style="display: none">
          <th colspan="2">No matching files</th>
        </tr>
        <tbody class="js-results-list">
        </tbody>
      </table>
    </div>

    <div id="jump-to-line" style="display:none">
      <h2>Jump to Line</h2>
      <form>
        <input class="textfield" type="text">
        <div class="full-button">
          <button type="submit" class="classy">
            <span>Go</span>
          </button>
        </div>
      </form>
    </div>


        

      </div><!-- /.pagehead -->

      

  













  <div class="commit commit-tease js-details-container">
  
  <p class="commit-title">
    <a href="/avrilcoghlan/LittleBookofRMultivariateAnalysis/commit/781a1ba06b3c4a367dc3e368cedce5a429954c76">updated LDA</a>
    
  </p>
  
  <div class="commit-meta">
    <a href="/avrilcoghlan/LittleBookofRMultivariateAnalysis/commit/781a1ba06b3c4a367dc3e368cedce5a429954c76" class="sha-block">commit <span class="sha">781a1ba06b</span></a>

    <div class="authorship">
      
      <img src="https://secure.gravatar.com/avatar/7e5b70fe19e67f2a228c8b82fc58d653?s=140&d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-140.png" alt="" width="20" height="20" class="gravatar" />
      <span class="author-name"><a href="/avrilcoghlan">avrilcoghlan</a></span>
      authored <time class="js-relative-date" datetime="2011-08-31T03:33:32-07:00" title="2011-08-31 03:33:32">August 31, 2011</time>

      
    </div>
  </div>
</div>




  <div id="slider">

  

    <div class="breadcrumb" data-path="src/multivariateanalysis.rst/">
      <b><a href="/avrilcoghlan/LittleBookofRMultivariateAnalysis/tree/781a1ba06b3c4a367dc3e368cedce5a429954c76" class="js-rewrite-sha">LittleBookofRMultivariateAnalysis</a></b> / <a href="/avrilcoghlan/LittleBookofRMultivariateAnalysis/tree/781a1ba06b3c4a367dc3e368cedce5a429954c76/src" class="js-rewrite-sha">src</a> / multivariateanalysis.rst       <span style="display:none" id="clippy_3105" class="clippy">src/multivariateanalysis.rst</span>
      
      <object classid="clsid:d27cdb6e-ae6d-11cf-96b8-444553540000"
              width="110"
              height="14"
              class="clippy"
              id="clippy" >
      <param name="movie" value="https://a248.e.akamai.net/assets.github.com/flash/clippy.swf?v5"/>
      <param name="allowScriptAccess" value="always" />
      <param name="quality" value="high" />
      <param name="scale" value="noscale" />
      <param NAME="FlashVars" value="id=clippy_3105&amp;copied=copied!&amp;copyto=copy to clipboard">
      <param name="bgcolor" value="#FFFFFF">
      <param name="wmode" value="opaque">
      <embed src="https://a248.e.akamai.net/assets.github.com/flash/clippy.swf?v5"
             width="110"
             height="14"
             name="clippy"
             quality="high"
             allowScriptAccess="always"
             type="application/x-shockwave-flash"
             pluginspage="http://www.macromedia.com/go/getflashplayer"
             FlashVars="id=clippy_3105&amp;copied=copied!&amp;copyto=copy to clipboard"
             bgcolor="#FFFFFF"
             wmode="opaque"
      />
      </object>
      

    </div>

    <div class="frames">
      <div class="frame frame-center" data-path="src/multivariateanalysis.rst/" data-permalink-url="/avrilcoghlan/LittleBookofRMultivariateAnalysis/blob/781a1ba06b3c4a367dc3e368cedce5a429954c76/src/multivariateanalysis.rst" data-title="src/multivariateanalysis.rst at master from avrilcoghlan/LittleBookofRMultivariateAnalysis - GitHub" data-type="blob">
        
          <ul class="big-actions">
            
            <li><a class="file-edit-link minibutton" href="/avrilcoghlan/LittleBookofRMultivariateAnalysis/edit/__current_ref__/src/multivariateanalysis.rst"><span>Edit this file</span></a></li>
          </ul>
        

        <div id="files">
          <div class="file">
            <div class="meta">
              <div class="info">
                <span class="icon"><img alt="Txt" height="16" src="https://a248.e.akamai.net/assets.github.com/images/icons/txt.png" width="16" /></span>
                <span class="mode" title="File Mode">100644</span>
                
                  <span>1830 lines (1465 sloc)</span>
                
                <span>89.401 kb</span>
              </div>
              <ul class="actions">
                <li><a href="/avrilcoghlan/LittleBookofRMultivariateAnalysis/raw/master/src/multivariateanalysis.rst" id="raw-url">raw</a></li>
                
                  <li><a href="/avrilcoghlan/LittleBookofRMultivariateAnalysis/blame/master/src/multivariateanalysis.rst">blame</a></li>
                
                <li><a href="/avrilcoghlan/LittleBookofRMultivariateAnalysis/commits/master/src/multivariateanalysis.rst">history</a></li>
              </ul>
            </div>
            
  <div id="readme" class="blob instapaper_body">
    <div class="wikistyle"> 
 
<h1>Using R for Multivariate Analysis</h1>
 
<h2>Multivariate Analysis</h2>
<p>This booklet tells you how to use the R statistical software to carry out some simple multivariate analyses,
with a focus on principal components analysis (PCA) and linear discriminant analysis (LDA).</p>
<p>This booklet assumes that the reader has some basic knowledge of multivariate analyses, and
the principal focus of the booklet is not to explain multivariate analyses, but rather
to explain how to carry out these analyses using R.</p>
<p>If you are new to multivariate analysis, and want to learn more about any of the concepts
presented here, I would highly recommend the Open University book
"Multivariate Analysis" (product code M249/03), available from
from <a href="http://www.ouw.co.uk/store/">the Open University Shop</a>.</p>
<p>In the examples in this booklet, I will be using data sets from the UCI Machine
Learning Repository, <a href="http://archive.ics.uci.edu/ml">http://archive.ics.uci.edu/ml</a>.</p>
<p>There is a pdf version of this booklet available at
<a href="https://github.com/avrilcoghlan/LittleBookofRTimeSeries/raw/master/_build/latex/MultivariateAnalysis.pdf">https://github.com/avrilcoghlan/LittleBookofRTimeSeries/ raw/master/_build/latex/MultivariateAnalysis.pdf</a>.</p>
<p>If you like this booklet, you may also like to check out my booklet on using
R for biomedical statistics,
<a href="http://a-little-book-of-r-for-biomedical-statistics.readthedocs.org/">http://a-little-book-of-r-for-biomedical-statistics.readthedocs.org/</a>,
and my booklet on using R for time series analysis,
<a href="http://a-little-book-of-r-for-time-series.readthedocs.org/">http://a-little-book-of-r-for-time-series.readthedocs.org/</a>.</p>
 
 
<h2>Reading Multivariate Analysis Data into R</h2>
<p>The first thing that you will want to do to analyse your multivariate data will be to read
it into R, and to plot the data. You can read data into R using the read.table() function.</p>
<p>For example, the file <a href="http://archive.ics.uci.edu/ml/machine-learning-databases/wine/wine.data">http://archive.ics.uci.edu/ml/machine-learning-databases/wine/wine.data</a>
contains data on concentrations of 13 different chemicals in wines grown in the same region in Italy that are
derived from three different cultivars.</p>
<p>The data set looks like this:</p>
<pre>
1,14.23,1.71,2.43,15.6,127,2.8,3.06,.28,2.29,5.64,1.04,3.92,1065
1,13.2,1.78,2.14,11.2,100,2.65,2.76,.26,1.28,4.38,1.05,3.4,1050
1,13.16,2.36,2.67,18.6,101,2.8,3.24,.3,2.81,5.68,1.03,3.17,1185
1,14.37,1.95,2.5,16.8,113,3.85,3.49,.24,2.18,7.8,.86,3.45,1480
1,13.24,2.59,2.87,21,118,2.8,2.69,.39,1.82,4.32,1.04,2.93,735
...
</pre>
<p>There is one row per wine sample.
The first column contains the cultivar of a wine sample (labelled 1, 2 or 3), and the following thirteen columns
contain the concentrations of the 13 different chemicals in that sample.
The columns are separated by commas.</p>
<p>When we read the file into R using the read.table() function, we need to use the "sep="
argument in read.table() to tell it that the columns are separated by commas.
That is, we can read in the file using the read.table() function as follows:</p>
<pre>
&gt; wine &lt;- read.table("http://archive.ics.uci.edu/ml/machine-learning-databases/wine/wine.data",
          sep=",")
&gt; wine
     V1    V2   V3   V4   V5  V6   V7   V8   V9  V10       V11   V12  V13  V14
 1    1 14.23 1.71 2.43 15.6 127 2.80 3.06 0.28 2.29  5.640000 1.040 3.92 1065
 2    1 13.20 1.78 2.14 11.2 100 2.65 2.76 0.26 1.28  4.380000 1.050 3.40 1050
 3    1 13.16 2.36 2.67 18.6 101 2.80 3.24 0.30 2.81  5.680000 1.030 3.17 1185
 4    1 14.37 1.95 2.50 16.8 113 3.85 3.49 0.24 2.18  7.800000 0.860 3.45 1480
 5    1 13.24 2.59 2.87 21.0 118 2.80 2.69 0.39 1.82  4.320000 1.040 2.93  735
 ...
 176  3 13.27 4.28 2.26 20.0 120 1.59 0.69 0.43 1.35 10.200000 0.590 1.56  835
 177  3 13.17 2.59 2.37 20.0 120 1.65 0.68 0.53 1.46  9.300000 0.600 1.62  840
 178  3 14.13 4.10 2.74 24.5  96 2.05 0.76 0.56 1.35  9.200000 0.610 1.60  560
</pre>
<p>In this case the data on 178 samples of wine has been read into the variable 'wine'.</p>
 
 
<h2>Plotting Multivariate Data</h2>
<p>Once you have read a multivariate data set into R, the next step is usually to make a plot of the data.</p>
 
<h3>A Matrix Scatterplot</h3>
<p>One common way of plotting multivariate data is to make a "matrix scatterplot", showing each pair of
variables plotted against each other. We can use the "scatterplotMatrix()" function from the "car"
R package to do this. To use this function, we first need to install the "car" R package
(for instructions on how to install an R package, see <a href="./installr.html#how-to-install-an-r-package">How to install an R package</a>).</p>
<p>Once you have installed the "car" R package, you can load the "car" R package by typing:</p>
<pre>
&gt; library("car")
</pre>
<p>You can then use the "scatterplotMatrix()" function to plot the multivariate data.</p>
<p>To use the scatterplotMatrix() function, you need to give it as its input the variables
that you want included in the plot. Say for example, that we just want to include the
variables corresponding to the concentrations of the first five chemicals. These are stored in
columns 2-6 of the variable "wine". We can extract just these columns from the variable
"wine" by typing:</p>
<pre>
&gt; wine[2:6]
         V2   V3   V4   V5  V6
  1   14.23 1.71 2.43 15.6 127
  2   13.20 1.78 2.14 11.2 100
  3   13.16 2.36 2.67 18.6 101
  4   14.37 1.95 2.50 16.8 113
  5   13.24 2.59 2.87 21.0 118
  ...
</pre>
<p>To make a matrix scatterplot of just these 13 variables using the scatterplotMatrix() function we type:</p>
<pre>
&gt; scatterplotMatrix(wine[2:6])
</pre>
<p><img alt="image1" src="../_static/image1.png"></p>
<p>In this matrix scatterplot, the diagonal cells show histograms of each of the variables, in this
case the concentrations of the first five chemicals (variables V2, V3, V4, V5, V6).</p>
<p>Each of the off-diagonal cells is a scatterplot of two of the five chemicals, for example, the second cell in the
first row is a scatterplot of V2 (y-axis) against V3 (x-axis).</p>
 
 
<h3>A Scatterplot with the Data Points Labelled by their Group</h3>
<p>If you see an interesting scatterplot for two variables in the matrix scatterplot, you may want to
plot that scatterplot in more detail, with the data points labelled by their group (their cultivar in this case).</p>
<p>For example, in the matrix scatterplot above, the cell in the third column of the fourth row down is a scatterplot
of V5 (x-axis) against V4 (y-axis). If you look at this scatterplot, it appears that there may be a
positive relationship between V5 and V4.</p>
<p>We may therefore decide to examine the relationship between V5 and V4 more closely, by plotting a scatterplot
of these two variable, with the data points labelled by their group (their cultivar). To plot a scatterplot
of two variables, we can use the "plot" R function. The V4 and V5 variables are stored in the columns
V4 and V5 of the variable "wine", so can be accessed by typing wine$V4 or wine$V5. Therefore, to plot
the scatterplot, we type:</p>
<pre>
&gt; plot(wine$V4, wine$V5)
</pre>
<p><img alt="image2" src="../_static/image2.png"></p>
<p>If we want to label the data points by their group (the cultivar of wine here), we can use the "text" function
in R to plot some text beside every data point. In this case, the cultivar of wine is stored in the column
V1 of the variable "wine", so we type:</p>
<pre>
&gt; text(wine$V4, wine$V5, wine$V1, cex=0.7, pos=4, col="red")
</pre>
<p>If you look at the help page for the "text" function, you will see that "pos=4" will plot the text just to the
right of the symbol for a data point. The "cex=0.5" option will plot the text at half the default size, and
the "col=red" option will plot the text in red. This gives us the following plot:</p>
<p><img alt="image4" src="../_static/image4.png"></p>
<p>We can see from the scatterplot of V4 versus V5 that the wines from cultivar 2 seem to have
lower values of V4 compared to the wines of cultivar 1.</p>
 
 
<h3>A Profile Plot</h3>
<p>Another type of plot that is useful is a "profile plot", which shows the variation in each of the
variables, by plotting the value of each of the variables for each of the samples.</p>
<p>The function "makeProfilePlot()" below can be used to make a profile plot. This function requires
the "RColorBrewer" library. To use this function, we first need to install the "RColorBrewer" R package
(for instructions on how to install an R package, see <a href="./installr.html#how-to-install-an-r-package">How to install an R package</a>).</p>
<pre>
&gt; makeProfilePlot &lt;- function(mylist,names)
  {
     require(RColorBrewer)
     # find out how many variables we want to include
     numvariables &lt;- length(mylist)
     # choose 'numvariables' random colours
     colours &lt;- brewer.pal(numvariables,"Set1")
     # find out the minimum and maximum values of the variables:
     mymin &lt;- 1e+20
     mymax &lt;- 1e-20
     for (i in 1:numvariables)
     {
        vectori &lt;- mylist[[i]]
        mini &lt;- min(vectori)
        maxi &lt;- max(vectori)
        if (mini &lt; mymin) { mymin &lt;- mini }
        if (maxi &gt; mymax) { mymax &lt;- maxi }
     }
     # plot the variables
     for (i in 1:numvariables)
     {
        vectori &lt;- mylist[[i]]
        namei &lt;- names[i]
        colouri &lt;- colours[i]
        if (i == 1) { plot(vectori,col=colouri,type="l",ylim=c(mymin,mymax)) }
        else         { points(vectori, col=colouri,type="l")                                     }
        lastxval &lt;- length(vectori)
        lastyval &lt;- vectori[length(vectori)]
        text((lastxval-10),(lastyval),namei,col="black",cex=0.6)
     }
  }
</pre>
<p>To use this function, you first need to copy and paste it into R. The arguments to the
function are a vector containing the names of the varibles that you want to plot, and
a list variable containing the variables themselves.</p>
<p>For example, to make a profile plot of the concentrations of the first five chemicals in the wine samples
(stored in columns V2, V3, V4, V5, V6 of variable "wine"), we type:</p>
<pre>
&gt; library(RColorBrewer)
&gt; names &lt;- c("V2","V3","V4","V5","V6")
&gt; mylist &lt;- list(wine$V2,wine$V3,wine$V4,wine$V5,wine$V6)
&gt; makeProfilePlot(mylist,names)
</pre>
<p><img alt="image5" src="../_static/image5.png"></p>
<p>It is clear from the profile plot that the mean and standard deviation for V6 is
quite a lot higher than that for the other variables.</p>
 
 
 
<h2>Calculating Summary Statistics for Multivariate Data</h2>
<p>Another thing that you are likely to want to do is to calculate summary statistics such as the
mean and standard deviation for each of the variables in your multivariate data set.</p>
<p>This is easy to do, using the "mean()" and "sd()" functions in R. For example, say we want
to calculate the mean and standard deviations of each of the 13 chemical concentrations in the
wine samples. These are stored in columns 2-14 of the variable "wine". So we type:</p>
<pre>
&gt; mean(wine[2:14])
          V2          V3          V4          V5          V6          V7
  13.0006180   2.3363483   2.3665169  19.4949438  99.7415730   2.2951124
          V8          V9         V10         V11         V12         V13
   2.0292697   0.3618539   1.5908989   5.0580899   0.9574494   2.6116854
          V14
 746.8932584
</pre>
<p>This tells us that the mean of variable V2 is 13.0006180, the mean of V3 is 2.3363483, and so on.</p>
<p>Similarly, to get the standard deviations of the 13 chemical concentrations, we type:</p>
<pre>
&gt; sd(wine[2:14])
          V2          V3          V4          V5          V6          V7
   0.8118265   1.1171461   0.2743440   3.3395638  14.2824835   0.6258510
          V8          V9         V10         V11         V12         V13
   0.9988587   0.1244533   0.5723589   2.3182859   0.2285716   0.7099904
          V14
 314.9074743
</pre>
<p>We can see here that it would make sense to standardise in order to compare the variables because the variables
have very different standard deviations - the standard deviation of V14 is 314.9074743, while the standard deviation
of V9 is just 0.1244533. Thus, in order to compare the variables, we need to standardise each variable so that
it has a sample variance of 1 and sample mean of 0. We will explain below how to standardise the variables.</p>
 
<h3>Means and Variances Per Group</h3>
<p>It is often interesting to calculate the means and standard deviations for just the samples
from a particular group, for example, for the wine samples from each cultivar. The cultivar
is stored in the column "V1" of the variable "wine".</p>
<p>To extract out the data for just cultivar 2, we can type:</p>
<pre>
&gt; cultivar2wine &lt;- wine[wine$V1=="2",]
</pre>
<p>We can then calculate the mean and standard deviations of the 13 chemicals' concentrations, for
just the cultivar 2 samples:</p>
<pre>
&gt; mean(cultivar2wine[2:14])
    V2         V3         V4         V5         V6         V7         V8
  12.278732   1.932676   2.244789  20.238028  94.549296   2.258873   2.080845
    V9        V10        V11        V12        V13        V14
  0.363662   1.630282   3.086620   1.056282   2.785352 519.507042
&gt; sd(cultivar2wine[2:14])
    V2          V3          V4          V5          V6          V7          V8
  0.5379642   1.0155687   0.3154673   3.3497704  16.7534975   0.5453611   0.7057008
    V9         V10         V11         V12         V13         V14
  0.1239613   0.6020678   0.9249293   0.2029368   0.4965735 157.2112204
</pre>
<p>You can calculate the mean and standard deviation of the 13 chemicals' concentrations for just cultivar 1 samples,
or for just cultivar 3 samples, in a similar way.</p>
<p>However, for convenience, you might want to use the function "printMeanAndSdByGroup()" below, which
prints out the mean and standard deviation of the variables for each group in your data set:</p>
<pre>
&gt; printMeanAndSdByGroup &lt;- function(variables,groupvariable)
  {
     # find out how many variables we have
     variables &lt;- as.data.frame(variables)
     numvariables &lt;- length(variables)
     # find out how many values the group variable can take
     groupvariable2 &lt;- as.factor(groupvariable[[1]])
     levels &lt;- levels(groupvariable2)
     numlevels &lt;- length(levels)
     for (i in 1:numlevels)
     {
        leveli &lt;- levels[i]
        levelidata &lt;- variables[groupvariable==leveli,]
        groupsize &lt;- nrow(levelidata)
        print(paste("Group",leveli,"Group size:",groupsize))
        print(paste("Group",leveli,"Means:"))
        print(mean(levelidata))
        print(paste("Group",leveli,"Standard Deviations:"))
        print(sd(levelidata))
     }
  }
</pre>
<p>To use the function "printMeanAndSdByGroup()", you first need to copy and paste it into R. The
arguments of the function are the variables that you want to calculate means and standard deviations for,
and the variable containing the group of each sample. For example, to calculate the mean and standard deviation
for each of the 13 chemical concentrations, for each of the three different wine cultivars, we type:</p>
<pre>
&gt; printMeanAndSdByGroup(wine[2:14],wine[1])
  [1] "Group 1 Group size: 59"
  [1] "Group 1 Means:"
     V2          V3          V4          V5          V6          V7          V8
  13.744746    2.010678    2.455593   17.037288  106.338983    2.840169    2.982373
     V9         V10         V11         V12         V13         V14
  0.290000    1.899322    5.528305    1.062034    3.157797 1115.711864
  [1] "Group 1 Standard Deviations:"
      V2           V3           V4           V5           V6           V7
  0.46212536   0.68854886   0.22716598   2.54632245  10.49894932   0.33896135
      V8           V9          V10          V11          V12          V13
  0.39749361   0.07004924   0.41210923   1.23857281   0.11648264   0.35707658
     V14
  221.52076659
  [1] "Group 2 Group size: 71"
  [1] "Group 2 Means:"
    V2         V3         V4         V5         V6         V7         V8
  12.278732   1.932676   2.244789  20.238028  94.549296   2.258873   2.080845
    V9        V10        V11        V12        V13        V14
  0.363662   1.630282   3.086620   1.056282   2.785352 519.507042
  [1] "Group 2 Standard Deviations:"
     V2          V3          V4          V5          V6          V7          V8
  0.5379642   1.0155687   0.3154673   3.3497704  16.7534975   0.5453611   0.7057008
     V9         V10         V11         V12         V13         V14
  0.1239613   0.6020678   0.9249293   0.2029368   0.4965735 157.2112204
  [1] "Group 3 Group size: 48"
  [1] "Group 3 Means:"
     V2          V3          V4          V5          V6          V7          V8
  13.1537500   3.3337500   2.4370833  21.4166667  99.3125000   1.6787500   0.7814583
     V9         V10         V11         V12         V13         V14
  0.4475000   1.1535417   7.3962500   0.6827083   1.6835417 629.8958333
  [1] "Group 3 Standard Deviations:"
     V2          V3          V4          V5          V6          V7          V8
  0.5302413   1.0879057   0.1846902   2.2581609  10.8904726   0.3569709   0.2935041
     V9         V10         V11         V12         V13         V14
  0.1241396   0.4088359   2.3109421   0.1144411   0.2721114 115.0970432
</pre>
<p>The function "printMeanAndSdByGroup()" also prints out the number of samples in each group. In this case,
we see that there are 59 samples of cultivar 1, 71 of cultivar 2, and 48 of cultivar 3.</p>
 
 
<h3>Between-groups Variance and Within-groups Variance for a Variable</h3>
<p>If we want to calculate the within-groups variance for a particular variable (for example, for a particular
chemical's concentration), we can use the function "calcWithinGroupsVariance()" below:</p>
<pre>
&gt; calcWithinGroupsVariance &lt;- function(variable,groupvariable)
  {
     # find out how many values the group variable can take
     groupvariable2 &lt;- as.factor(groupvariable[[1]])
     levels &lt;- levels(groupvariable2)
     numlevels &lt;- length(levels)
     # get the mean and standard deviation for each group:
     numtotal &lt;- 0
     denomtotal &lt;- 0
     for (i in 1:numlevels)
     {
        leveli &lt;- levels[i]
        levelidata &lt;- variable[groupvariable==leveli,]
        levelilength &lt;- length(levelidata)
        # get the mean and standard deviation for group i:
        meani &lt;- mean(levelidata)
        sdi &lt;- sd(levelidata)
        numi &lt;- (levelilength - 1)*(sdi * sdi)
        denomi &lt;- levelilength
        numtotal &lt;- numtotal + numi
        denomtotal &lt;- denomtotal + denomi
     }
     # calculate the within-groups variance
     Vw &lt;- numtotal / (denomtotal - numlevels)
     return(Vw)
  }
</pre>
<p>You will need to copy and paste this function into R before you can use it.
For example, to calculate the within-groups variance of the variable V2 (the concentration of the first chemical),
we type:</p>
<pre>
&gt; calcWithinGroupsVariance(wine[2],wine[1])
  [1] 0.2620525
</pre>
<p>Thus, the within-groups variance for V2 is 0.2620525.</p>
<p>We can calculate the between-groups variance for a particular variable (eg. V2) using the function
"calcBetweenGroupsVariance()" below:</p>
<pre>
&gt; calcBetweenGroupsVariance &lt;- function(variable,groupvariable)
  {
     # find out how many values the group variable can take
     groupvariable2 &lt;- as.factor(groupvariable[[1]])
     levels &lt;- levels(groupvariable2)
     numlevels &lt;- length(levels)
     # calculate the overall grand mean:
     grandmean &lt;- mean(variable)
     # get the mean and standard deviation for each group:
     numtotal &lt;- 0
     denomtotal &lt;- 0
     for (i in 1:numlevels)
     {
        leveli &lt;- levels[i]
        levelidata &lt;- variable[groupvariable==leveli,]
        levelilength &lt;- length(levelidata)
        # get the mean and standard deviation for group i:
        meani &lt;- mean(levelidata)
        sdi &lt;- sd(levelidata)
        numi &lt;- levelilength * ((meani - grandmean)^2)
        denomi &lt;- levelilength
        numtotal &lt;- numtotal + numi
        denomtotal &lt;- denomtotal + denomi
     }
     # calculate the between-groups variance
     Vb &lt;- numtotal / (numlevels - 1)
     Vb &lt;- Vb[[1]]
     return(Vb)
  }
</pre>
<p>Once you have copied and pasted this function into R, you can use it to calculate the between-groups
variance for a variable such as V2:</p>
<pre>
&gt; calcBetweenGroupsVariance (wine[2],wine[1])
  [1] 35.39742
</pre>
<p>Thus, the between-groups variance of V2 is 35.39742.</p>
<p>We can calculate the "separation" achieved by a variable as its between-groups variance devided by its
within-groups variance. Thus, the separation achieved by V2 is calculated as:</p>
<pre>
&gt; 35.39742/0.2620525
  [1] 135.0776
</pre>
<p>If you want to calculate the separations achieved by all of the variables in a multivariate data set,
you can use the function "calcSeparations()" below:</p>
<pre>
&gt; calcSeparations &lt;- function(variables,groupvariable)
  {
     # find out how many variables we have
     variables &lt;- as.data.frame(variables)
     numvariables &lt;- length(variables)
     # find the variable names
     variablenames &lt;- colnames(variables)
     # calculate the separation for each variable
     for (i in 1:numvariables)
     {
        variablei &lt;- variables[i]
        variablename &lt;- variablenames[i]
        Vw &lt;- calcWithinGroupsVariance(variablei, groupvariable)
        Vb &lt;- calcBetweenGroupsVariance(variablei, groupvariable)
        sep &lt;- Vb/Vw
        print(paste("variable",variablename,"Vw=",Vw,"Vb=",Vb,"separation=",sep))
     }
  }
</pre>
<p>For example, to calculate the separations for each of the 13 chemical concentrations, we type:</p>
<pre>
&gt; calcSeparations(wine[2:14],wine[1])
  [1] "variable V2 Vw= 0.262052469153907 Vb= 35.3974249602692 separation= 135.0776242428"
  [1] "variable V3 Vw= 0.887546796746581 Vb= 32.7890184869213 separation= 36.9434249631837"
  [1] "variable V4 Vw= 0.0660721013425184 Vb= 0.879611357248741 separation= 13.312901199991"
  [1] "variable V5 Vw= 8.00681118121156 Vb= 286.41674636309 separation= 35.7716374073093"
  [1] "variable V6 Vw= 180.65777316441 Vb= 2245.50102788939 separation= 12.4295843381499"
  [1] "variable V7 Vw= 0.191270475224227 Vb= 17.9283572942847 separation= 93.7330096203673"
  [1] "variable V8 Vw= 0.274707514337437 Vb= 64.2611950235641 separation= 233.925872681549"
  [1] "variable V9 Vw= 0.0119117022132797 Vb= 0.328470157461624 separation= 27.5754171469659"
  [1] "variable V10 Vw= 0.246172943795542 Vb= 7.45199550777775 separation= 30.2713831702276"
  [1] "variable V11 Vw= 2.28492308133354 Vb= 275.708000822304 separation= 120.664018441003"
  [1] "variable V12 Vw= 0.0244876469432414 Vb= 2.48100991493829 separation= 101.3167953903"
  [1] "variable V13 Vw= 0.160778729560982 Vb= 30.5435083544253 separation= 189.972320578889"
  [1] "variable V14 Vw= 29707.6818705169 Vb= 6176832.32228483 separation= 207.920373902178"
</pre>
<p>Thus, the individual variable which gives the greatest separations between the groups (the wine cultivars) is
V8 (separation 233.9). As we will discuss below, the purpose of linear discriminant analysis (LDA) is to find the
linear combination of the individual variables that will give the greatest separation between the groups (cultivars here).
This hopefully will give a better separation than the best separation achievable by any individual variable (233.9
for V8 here).</p>
 
 
<h3>Between-groups Covariance and Within-groups Covariance for Two Variables</h3>
<p>If you have a multivariate data set with several variables describing sampling units from different groups,
such as the wine samples from different cultivars, it is often of interest to calculate the within-groups
covariance and between-groups variance for pairs of the variables.</p>
<p>This can be done using the following functions, which you will need to copy and paste into R to use them:</p>
<pre>
&gt; calcWithinGroupsCovariance &lt;- function(variable1,variable2,groupvariable)
  {
     # find out how many values the group variable can take
     groupvariable2 &lt;- as.factor(groupvariable[[1]])
     levels &lt;- levels(groupvariable2)
     numlevels &lt;- length(levels)
     # get the covariance of variable 1 and variable 2 for each group:
     Covw &lt;- 0
     for (i in 1:numlevels)
     {
        leveli &lt;- levels[i]
        levelidata1 &lt;- variable1[groupvariable==leveli,]
        levelidata2 &lt;- variable2[groupvariable==leveli,]
        mean1 &lt;- mean(levelidata1)
        mean2 &lt;- mean(levelidata2)
        levelilength &lt;- length(levelidata1)
        # get the covariance for this group:
        term1 &lt;- 0
        for (j in 1:levelilength)
        {
           term1 &lt;- term1 + ((levelidata1[j] - mean1)*(levelidata2[j] - mean2))
        }
        Cov_groupi &lt;- term1 # covariance for this group
        Covw &lt;- Covw + Cov_groupi
     }
     totallength &lt;- nrow(variable1)
     Covw &lt;- Covw / (totallength - numlevels)
     return(Covw)
  }
</pre>
<p>For example, to calculate the within-groups covariance for variables V8 and V11, we type:</p>
<pre>
&gt; calcWithinGroupsCovariance(wine[8],wine[11],wine[1])
  [1] 0.2866783
</pre>
<pre>
&gt; calcBetweenGroupsCovariance &lt;- function(variable1,variable2,groupvariable)
  {
     # find out how many values the group variable can take
     groupvariable2 &lt;- as.factor(groupvariable[[1]])
     levels &lt;- levels(groupvariable2)
     numlevels &lt;- length(levels)
     # calculate the grand means
     variable1mean &lt;- mean(variable1)
     variable2mean &lt;- mean(variable2)
     # calculate the between-groups covariance
     Covb &lt;- 0
     for (i in 1:numlevels)
     {
        leveli &lt;- levels[i]
        levelidata1 &lt;- variable1[groupvariable==leveli,]
        levelidata2 &lt;- variable2[groupvariable==leveli,]
        mean1 &lt;- mean(levelidata1)
        mean2 &lt;- mean(levelidata2)
        levelilength &lt;- length(levelidata1)
        term1 &lt;- (mean1 - variable1mean)*(mean2 - variable2mean)*(levelilength)
        Covb &lt;- Covb + term1
     }
     Covb &lt;- Covb / (numlevels - 1)
     Covb &lt;- Covb[[1]]
     return(Covb)
  }
</pre>
<p>For example, to calculate the between-groups covariance for variables V8 and V11, we type:</p>
<pre>
&gt; calcBetweenGroupsCovariance(wine[8],wine[11],wine[1])
  [1] -60.41077
</pre>
<p>Thus, for V8 and V11, the between-groups covariance is -60.41 and the within-groups covariance is 0.29.
Since the within-groups covariance is positive (0.29), it means V8 and V11 are positively related within groups:
for individuals from the same group, individuals with a high value of V8 tend to have a high value of V11,
and vice versa. Since the between-groups covariance is negative (-60.41), V8 and V11 are negatively related between groups:
groups with a high mean value of V8 tend to have a low mean value of V11, and vice versa.</p>
 
 
 
<h2>Calculating Correlations for Multivariate Data</h2>
<p>It is often of interest to investigate whether any of the variables in a multivariate data set are
significantly correlated.</p>
<p>To calculate the linear (Pearson) correlation coefficient for a pair of variables, you can use
the "cor.test()" function in R. For example, to calculate the correlation coefficient for the first
two chemicals' concentrations, V2 and V3, we type:</p>
<pre>
&gt; cor.test(wine$V2, wine$V3)
  Pearson's product-moment correlation
  data:  wine$V2 and wine$V3
  t = 1.2579, df = 176, p-value = 0.2101
  alternative hypothesis: true correlation is not equal to 0
  95 percent confidence interval:
  -0.05342959  0.23817474
  sample estimates:
   cor
  0.09439694
</pre>
<p>This tells us that the correlation coefficient is about 0.094, which is a very weak correlation.
Furthermore, the P-value for the statistical test of whether the correlation coefficient is
significantly different from zero is 0.21. This is much greater than 0.05 (which we can use here
as a cutoff for statistical significance), so there is very weak evidence that that the correlation is non-zero.</p>
<p>If you have a lot of variables, you can use "cor.test()" to calculate the correlation coefficient
for each pair of variables, but you might be just interested in finding out what are the most highly
correlated pairs of variables. For this you can use the function "mosthighlycorrelated()" below.</p>
<p>The function "mosthighlycorrelated()" will print out the linear correlation coefficients for
each pair of variables in your data set, in order of the correlation coefficient. This lets you see
very easily which pair of variables are most highly correlated.</p>
<pre>
&gt; mosthighlycorrelated &lt;- function(mydataframe,numtoreport)
  {
     # find the correlations
     cormatrix &lt;- cor(mydataframe)
     # set the correlations on the diagonal or lower triangle to zero,
     # so they will not be reported as the highest ones:
     diag(cormatrix) &lt;- 0
     cormatrix[lower.tri(cormatrix)] &lt;- 0
     # find the dimensions of the matrix, and the row names:
     numrows &lt;- nrow(cormatrix)
     therownames &lt;- rownames(cormatrix)
     # find the highest correlations
     sorted &lt;- sort(abs(cormatrix),decreasing=TRUE)
     for (i in 1:numtoreport)
     {
        corri &lt;- sorted[i]
        # find the pair of variables with this correlation
        for (j in 1:(numrows-1))
        {
           for (k in (j+1):numrows)
           {
              corrjk &lt;- cormatrix[j,k]
              if (corri == abs(corrjk))
              {
                 rowname &lt;- therownames[j]
                 colname &lt;- therownames[k]
                 print(paste("i=",i,"variables",rowname,"and",colname,"correlation=",corrjk))
              }
           }
        }
     }
  }
</pre>
<p>To use this function, you will first have to copy and paste it into R. The arguments of the function
are the variables that you want to calculate the correlations for, and the number of top correlation
coefficients to print out (for example, you can tell it to print out the largest ten correlation coefficients, or
the largest 20).</p>
<p>For example, to calculate correlation coefficients between the concentrations of the 13 chemicals
in the wine samples, and to print out the top 10 pairwise correlation coefficients, you can type:</p>
<pre>
&gt; mosthighlycorrelated(wine[2:14], 10)
  [1] "i= 1 variables V7 and V8 correlation= 0.864563500095115"
  [1] "i= 2 variables V8 and V13 correlation= 0.787193901866952"
  [1] "i= 3 variables V7 and V13 correlation= 0.699949364791186"
  [1] "i= 4 variables V8 and V10 correlation= 0.652691768607515"
  [1] "i= 5 variables V2 and V14 correlation= 0.643720037178213"
  [1] "i= 6 variables V7 and V10 correlation= 0.612413083780036"
  [1] "i= 7 variables V12 and V13 correlation= 0.565468293182659"
  [1] "i= 8 variables V3 and V12 correlation= -0.561295688664945"
  [1] "i= 9 variables V2 and V11 correlation= 0.546364195083704"
  [1] "i= 10 variables V8 and V12 correlation= 0.54347856648999"
</pre>
<p>This tells us that the pair of variables with the highest linear correlation coefficient are
V7 and V8 (correlation = 0.86 approximately).</p>
 
 
<h2>Standardising Variables</h2>
<p>If you want to compare different variables that have different units, are very different variances,
it is a good idea to first standardise the variables.</p>
<p>For example, we found above that the concentrations of the 13 chemicals in the wine samples show a wide range of
standard deviations, from 0.1244533 for V9 (variance 0.01548862) to 314.9074743 for V14 (variance 99166.72).
This is a range of approximately 6,402,554-fold in the variances.</p>
<p>As a result, it is not a good idea to use the unstandardised chemical concentrations as the input for a
principal component analysis (PCA, see below) of the
wine samples, as if you did that, the first principal component would be dominated by the variables
which show the largest variances, such as V14.</p>
<p>Thus, it would be a better idea to first standardise the variables so that they all have variance 1 and mean 0,
and to then carry out the principal component analysis on the standardised data. This would allow us to
find the principal components that provide the best low-dimensional representation of the variation in the
original data, without being overly biased by those variables that show the most variance in the original data.</p>
<p>You can standardise variables in R using the "scale()" function.</p>
<p>For example, to standardise the concentrations of the 13 chemicals in the wine samples, we type:</p>
<pre>
&gt; standardisedconcentrations &lt;- as.data.frame(scale(wine[2:14]))
</pre>
<p>Note that we use the "as.data.frame()" function to convert the output of "scale()" into a
"data frame", which is the same type of R variable that the "wine" variable.</p>
<p>We can check that each of the standardised variables stored in "standardisedconcentrations"
has a mean of 0 and a standard deviation of 1 by typing:</p>
<pre>
&gt; mean(standardisedconcentrations)
       V2            V3            V4            V5            V6            V7
  -8.591766e-16 -6.776446e-17  8.045176e-16 -7.720494e-17 -4.073935e-17 -1.395560e-17
       V8            V9           V10           V11           V12           V13
  6.958263e-17 -1.042186e-16 -1.221369e-16  3.649376e-17  2.093741e-16  3.003459e-16
      V14
  -1.034429e-16
&gt; sd(standardisedconcentrations)
  V2  V3  V4  V5  V6  V7  V8  V9 V10 V11 V12 V13 V14
  1   1   1   1   1   1   1   1   1   1   1   1   1
</pre>
<p>We see that the means of the standardised variables are all very tiny numbers and so are
essentially equal to 0, and the standard deviations of the standardised variables are all equal to 1.</p>
 
 
<h2>Principal Component Analysis</h2>
<p>The purpose of principal component analysis is to find the best low-dimensional representation of the variation in a
multivariate data set. For example, in the case of the wine data set, we have 13 chemical concentrations describing
wine samples from three different cultivars. We can carry out a principal component analysis to investigate
whether we can capture most of the variation between samples using a smaller number of new variables (principal
components), where each of these new variables is a linear combination of all or some of the 13 chemical concentrations.</p>
<p>To carry out a principal component analysis (PCA) on a multivariate data set, the first step is often to standardise
the variables under study using the "scale()" function (see above). This is necessary if the input variables
have very different variances, which is true in this case as the concentrations of the 13 chemicals have
very different variances (see above).</p>
<p>Once you have standardised your variables, you can carry out a principal component analysis using the "prcomp()"
function in R.</p>
<p>For example, to standardise the concentrations of the 13 chemicals in the wine samples, and carry out a
principal components analysis on the standardised concentrations, we type:</p>
<pre>
&gt; standardisedconcentrations &lt;- as.data.frame(scale(wine[2:14])) # standardise the variables
&gt; wine.pca &lt;- prcomp(standardisedconcentrations)                 # do a PCA
</pre>
<p>You can get a summary of the principal component analysis results using the "summary()" function on the
output of "prcomp()":</p>
<pre>
&gt; summary(wine.pca)
  Importance of components:
                          PC1   PC2   PC3    PC4    PC5    PC6    PC7    PC8    PC9   PC10
  Standard deviation     2.169 1.580 1.203 0.9586 0.9237 0.8010 0.7423 0.5903 0.5375 0.5009
  Proportion of Variance 0.362 0.192 0.111 0.0707 0.0656 0.0494 0.0424 0.0268 0.0222 0.0193
  Cumulative Proportion  0.362 0.554 0.665 0.7360 0.8016 0.8510 0.8934 0.9202 0.9424 0.9617
                          PC11   PC12    PC13
  Standard deviation     0.4752 0.4108 0.32152
  Proportion of Variance 0.0174 0.0130 0.00795
  Cumulative Proportion  0.9791 0.9920 1.00000
</pre>
<p>This gives us the standard deviation of each component, and the proportion of variance explained by
each component. The standard deviation of the components is stored in a named element called "sdev" of the output
variable made by "prcomp":</p>
<pre>
&gt; wine.pca$sdev
  [1] 2.1692972 1.5801816 1.2025273 0.9586313 0.9237035 0.8010350 0.7423128 0.5903367
  [9] 0.5374755 0.5009017 0.4751722 0.4108165 0.3215244
</pre>
<p>The total variance explained by the components is the sum of the variances of the components:</p>
<pre>
&gt; sum((wine.pca$sdev)^2)
  [1] 13
</pre>
<p>In this case, we see that the total variance is 13, which is equal to the number of standardised variables (13 variables).
This is because for standardised data, the variance of each standardised variable is 1. The total variance is equal to the sum
of the variances of the individual variables, and since the variance of each standardised variable is 1, the
total variance should be equal to the  number of variables (13 here).</p>
 
<h3>Deciding How Many Principal Components to Retain</h3>
<p>In order to decide how many principal components should be retained,
it is common to summarise the results of a principal components analysis by making a scree plot, which we
can do in R using the "screeplot()" function:</p>
<pre>
&gt; screeplot(wine.pca, type="lines")
</pre>
<p><img alt="image6" src="../_static/image6.png"></p>
<p>The most obvious change in slope in the scree plot occurs at component 4, which is the "elbow" of the
scree plot. Therefore, it cound be argued based on the basis of the scree plot that the first three
components should be retained.</p>
<p>Another way of deciding how many components to retain is to use Kaiser's criterion:
that we should only retain principal components for which the variance is above 1 (when principal
component analysis was applied to standardised data).  We can check this by finding the variance of each
of the principal components:</p>
<pre>
&gt; (wine.pca$sdev)^2
  [1] 4.7058503 2.4969737 1.4460720 0.9189739 0.8532282 0.6416570 0.5510283 0.3484974
  [9] 0.2888799 0.2509025 0.2257886 0.1687702 0.1033779
</pre>
<p>We see that the variance is above 1 for principal components 1, 2, and 3 (which have variances
4.71, 2.50, and 1.45, respectively). Therefore, using Kaiser's criterion, we would retain the first
three principal components.</p>
<p>A third way to decide how many principal components to retain is to decide to keep the number of
components required to explain at least some minimum amount of the total variance. For example, if
it is important to explain at least 80% of the variance, we would retain the first five principal components,
as we can see from the output of "summary(wine.pca)" that the first five principal components
explain 80.2% of the variance (while the first four components explain just 73.6%, so are not sufficient).</p>
 
 
<h3>Loadings for the Principal Components</h3>
<p>The loadings for the principal components are stored in a named element "rotation" of the variable
returned by "prcomp()". This contains a matrix with the loadings of each principal component, where
the first column in the matrix contains the loadings for the first principal component, the second
column contains the loadings for the second principal component, and so on.</p>
<p>Therefore, to obtain the loadings for the first principal component in our
analysis of the 13 chemical concentrations in wine samples, we type:</p>
<pre>
&gt; wine.pca$rotation[,1]
      V2           V3           V4           V5           V6           V7
  -0.144329395  0.245187580  0.002051061  0.239320405 -0.141992042 -0.394660845
      V8           V9          V10          V11          V12          V13
  -0.422934297  0.298533103 -0.313429488  0.088616705 -0.296714564 -0.376167411
     V14
  -0.286752227
</pre>
<p>This means that the first principal component is a linear combination of the variables:
-0.144*Z2 + 0.245*Z3 + 0.002*Z4 + 0.239*Z5 - 0.142*Z6 - 0.395*Z7 - 0.423*Z8 + 0.299*Z9
-0.313*Z10 + 0.089*Z11 - 0.297*Z12 - 0.376*Z13 - 0.287*Z14, where Z2, Z3, Z4...Z14 are
the standardised versions of the variables V2, V3, V4...V14 (that each
have mean of 0 and variance of 1).</p>
<p>Note that the square of the loadings sum to 1, as this is a constraint used in calculating the loadings:</p>
<pre>
&gt; sum((wine.pca$rotation[,1])^2)
  [1] 1
</pre>
<p>To calculate the values of the first principal component, we can define our own function to calculate
a principal component given the loadings and the input variables' values:</p>
<pre>
&gt; calcpc &lt;- function(variables,loadings)
  {
     # find the number of samples in the data set
     as.data.frame(variables)
     numsamples &lt;- nrow(variables)
     # make a vector to store the component
     pc &lt;- numeric(numsamples)
     # find the number of variables
     numvariables &lt;- length(variables)
     # calculate the value of the component for each sample
     for (i in 1:numsamples)
     {
        valuei &lt;- 0
        for (j in 1:numvariables)
        {
           valueij &lt;- variables[i,j]
           loadingj &lt;- loadings[j]
           valuei &lt;- valuei + (valueij * loadingj)
        }
        pc[i] &lt;- valuei
     }
     return(pc)
  }
</pre>
<p>We can then use the function to calculate the values of the first principal component for each sample in our
wine data:</p>
<pre>
&gt; calcpc(standardisedconcentrations, wine.pca$rotation[,1])
  [1] -3.30742097 -2.20324981 -2.50966069 -3.74649719 -1.00607049 -3.04167373 -2.44220051
  [8] -2.05364379 -2.50381135 -2.74588238 -3.46994837 -1.74981688 -2.10751729 -3.44842921
  [15] -4.30065228 -2.29870383 -2.16584568 -1.89362947 -3.53202167 -2.07865856 -3.11561376
  [22] -1.08351361 -2.52809263 -1.64036108 -1.75662066 -0.98729406 -1.77028387 -1.23194878
  [29] -2.18225047 -2.24976267 -2.49318704 -2.66987964 -1.62399801 -1.89733870 -1.40642118
  [36] -1.89847087 -1.38096669 -1.11905070 -1.49796891 -2.52268490 -2.58081526 -0.66660159
  ...
</pre>
<p>In fact, the values of the first principal component are stored in the variable wine.pca$x[,1]
that was returned by the "prcomp()" function, so we can compare those values to the ones that we
calculated, and they should agree:</p>
<pre>
&gt; wine.pca$x[,1]
  [1] -3.30742097 -2.20324981 -2.50966069 -3.74649719 -1.00607049 -3.04167373 -2.44220051
  [8] -2.05364379 -2.50381135 -2.74588238 -3.46994837 -1.74981688 -2.10751729 -3.44842921
  [15] -4.30065228 -2.29870383 -2.16584568 -1.89362947 -3.53202167 -2.07865856 -3.11561376
  [22] -1.08351361 -2.52809263 -1.64036108 -1.75662066 -0.98729406 -1.77028387 -1.23194878
  [29] -2.18225047 -2.24976267 -2.49318704 -2.66987964 -1.62399801 -1.89733870 -1.40642118
  [36] -1.89847087 -1.38096669 -1.11905070 -1.49796891 -2.52268490 -2.58081526 -0.66660159
  ...
</pre>
<p>We see that they do agree.</p>
<p>The first principal component has highest (in absolute value) loadings for V8 (-0.423), V7 (-0.395), V13 (-0.376),
V10 (-0.313), V12 (-0.297), V14 (-0.287), V9 (0.299), V3 (0.245), and V5 (0.239). The loadings for V8, V7, V13,
V10, V12 and V14 are negative, while those for V9, V3, and V5 are positive. Therefore, an interpretation of the
first principal component is that it represents a contrast between the concentrations of V8, V7, V13, V10, V12, and V14,
and the concentrations of V9, V3 and V5.</p>
<p>Similarly, we can obtain the loadings for the second principal component by typing:</p>
<pre>
&gt; wine.pca$rotation[,2]
      V2           V3           V4           V5           V6           V7
  0.483651548  0.224930935  0.316068814 -0.010590502  0.299634003  0.065039512
      V8           V9          V10          V11          V12          V13
  -0.003359812  0.028779488  0.039301722  0.529995672 -0.279235148 -0.164496193
     V14
  0.364902832
</pre>
<p>This means that the second principal component is a linear combination of the variables:
0.484*Z2 + 0.225*Z3 + 0.316*Z4 - 0.011*Z5 + 0.300*Z6 + 0.065*Z7 - 0.003*Z8 + 0.029*Z9
+ 0.039*Z10 + 0.530*Z11 - 0.279*Z12 - 0.164*Z13 + 0.365*Z14, where Z1, Z2, Z3...Z14
are the standardised versions of variables V2, V3, ... V14 that each have mean 0 and variance 1.</p>
<p>Note that the square of the loadings sum to 1, as above:</p>
<pre>
&gt; sum((wine.pca$rotation[,2])^2)
  [1] 1
</pre>
<p>The second principal component has highest loadings for V11 (0.530), V2 (0.484), V14 (0.365), V4 (0.316),
V6 (0.300), V12 (-0.279), and V3 (0.225). The loadings for V11, V2, V14, V4, V6 and V3 are positive, while
the loading for V12 is negative. Therefore, an interpretation of the second principal component is that
it represents a contrast between the concentrations of V11, V2, V14, V4, V6 and V3, and the concentration of
V12. Note that the loadings for V11 (0.530) and V2 (0.484) are the largest, so the contrast is mainly between
the concentrations of V11 and V2, and the concentration of V12.</p>
 
 
<h3>Scatterplots of the Principal Components</h3>
<p>The values of the principal components are stored in a named element "x" of the variable returned by
"prcomp()". This contains a matrix with the principal components, where the first column in the matrix
contains the first principal component, the second column the second component, and so on.</p>
<p>Thus, in our example, "wine.pca$x[,1]" contains the first principal component, and
"wine.pca$x[,2]" contains the second principal component.</p>
<p>We can make a scatterplot of the first two principal components, and label the data points with the cultivar that the wine
samples come from, by typing:</p>
<pre>
&gt; plot(wine.pca$x[,1],wine.pca$x[,2]) # make a scatterplot
&gt; text(wine.pca$x[,1],wine.pca$x[,2], wine$V1, cex=0.7, pos=4, col="red") # add labels
</pre>
<p><img alt="image7" src="../_static/image7.png"></p>
<p>The scatterplot shows the first principal component on the x-axis, and the second principal
component on the y-axis. We can see from the scatterplot that wine samples of cultivar 1
have much lower values of the first principal component than wine samples of cultivar 3.
Therefore, the first principal component separates wine samples of cultivars 1 from those
of cultivar 3.</p>
<p>We can also see that wine samples of cultivar 2 have much higher values of the second
principal component than wine samples of cultivars 1 and 3. Therefore, the second principal
component separates samples of cultivar 2 from samples of cultivars 1 and 3.</p>
<p>Therefore, the first two principal components are reasonably useful for distinguishing wine
samples of the three different cultivars.</p>
<p>Above, we interpreted the first principal component as a contrast between the concentrations of V8, V7, V13, V10, V12, and V14,
and the concentrations of V9, V3 and V5. We can check whether this makes sense in terms of the
concentrations of these chemicals in the different cultivars, by printing out the means of the
standardised concentration variables in each cultivar, using the "printMeanAndSdByGroup()" function (see above):</p>
<pre>
&gt; printMeanAndSdByGroup(standardisedconcentrations,wine[1])
  [1] "Group 1 Means:"
    V2         V3         V4         V5         V6         V7         V8
  0.9166093 -0.2915199  0.3246886 -0.7359212  0.4619232  0.8709055  0.9541923
    V9        V10        V11        V12        V13        V14
  -0.5773564  0.5388633  0.2028288  0.4575567  0.7691811  1.1711967
  [1] "Group 2 Means:"
     V2          V3          V4          V5          V6          V7          V8
  -0.88921161 -0.36134241 -0.44370614  0.22250941 -0.36354162 -0.05790375  0.05163434
     V9         V10         V11         V12         V13         V14
  0.01452785  0.06880790 -0.85039994  0.43239084  0.24460431 -0.72207310
  [1] "Group 3 Means:"
     V2          V3          V4          V5          V6          V7          V8
  0.18862653  0.89281222  0.25721896  0.57544128 -0.03004191 -0.98483874 -1.24923710
     V9         V10         V11         V12         V13         V14
  0.68817813 -0.76413110  1.00857281 -1.20199161 -1.30726231 -0.37152953
</pre>
<p>Does it make sense that the first principal component can separate cultivar 1 from cultivar 3?
In cultivar 1, the mean values of V8 (0.954), V7 (0.871), V13 (0.769), V10 (0.539), V12 (0.458) and V14 (1.171)
are very high compared to the mean values of V9 (-0.577), V3 (-0.292) and V5 (-0.736).
In cultivar 3, the mean values of V8 (-1.249), V7 (-0.985), V13 (-1.307), V10 (-0.764), V12 (-1.202) and V14 (-0.372)
are very low compared to the mean values of V9 (0.688), V3 (0.893) and V5 (0.575).
Therefore, it does make sense that principal component 1 is a contrast between the concentrations of V8, V7, V13, V10, V12, and V14,
and the concentrations of V9, V3 and V5; and that principal component 1 can separate cultivar 1 from cultivar 3.</p>
<p>Above, we intepreted the second principal component as a contrast between the concentrations of V11,
V2, V14, V4, V6 and V3, and the concentration of V12.
In the light of the mean values of these variables in the different cultivars, does
it make sense that the second principal component can separate cultivar 2 from cultivars 1 and 3?
In cultivar 1, the mean values of V11 (0.203), V2 (0.917), V14 (1.171), V4 (0.325), V6 (0.462) and V3 (-0.292)
are not very different from the mean value of V12 (0.458).
In cultivar 3, the mean values of V11 (1.009), V2 (0.189), V14 (-0.372), V4 (0.257), V6 (-0.030) and V3 (0.893)
are also not very different from the mean value of V12 (-1.202).
In contrast, in cultivar 2, the mean values of V11 (-0.850), V2 (-0.889), V14 (-0.722), V4 (-0.444), V6 (-0.364) and V3 (-0.361)
are much less than the mean value of V12 (0.432).
Therefore, it makes sense that principal component is a contrast between the concentrations of V11,
V2, V14, V4, V6 and V3, and the concentration of V12; and that principal component 2 can separate cultivar 2 from cultivars 1 and 3.</p>
 
 
 
<h2>Linear Discriminant Analysis</h2>
<p>The purpose of principal component analysis is to find the best low-dimensional representation of the variation in a
multivariate data set. For example, in the wine data set, we have 13 chemical concentrations describing wine samples from three cultivars.
By carrying out a principal component analysis, we found that most of the variation in the chemical concentrations
between the samples can be captured using the first two principal components,
where each of the principal components is a particular linear combination of the 13 chemical concentrations.</p>
<p>The purpose of linear discriminant analysis (LDA) is to find the linear combinations of the original variables (the 13
chemical concentrations here) that gives the best possible separation between the groups (wine cultivars here) in our
data set. Linear discriminant analysis is also known as "canonical discriminant analysis", or simply "discriminant analysis".</p>
<p>If we want to separate the wines by cultivar, the wines come from three different cultivars, so the number of groups (G) is 3,
and the number of variables is 13 (13 chemicals' concentrations; p = 13).  The maximum number of useful discriminant
functions that can separate the wines by cultivar is the minimum of G-1 and p, and so in this case it is the minimum of 2 and 13,
which is 2. Thus, we can find at most 2 useful discriminant functions to separate the wines by cultivar, using the
13 chemical concentration variables.</p>
<p>You can carry out a linear discriminant analysis using the "lda()" function from the R "MASS" package.
To use this function, we first need to install the "MASS" R package
(for instructions on how to install an R package, see <a href="./installr.html#how-to-install-an-r-package">How to install an R package</a>).</p>
<p>For example, to carry out a linear discriminant analysis using the 13 chemical concentrations in the wine samples, we type:</p>
<pre>
&gt; library("MASS")                                                # load the MASS package
&gt; wine.lda &lt;- lda(wine$V1 ~ wine$V2 + wine$V3 + wine$V4 + wine$V5 + wine$V6 + wine$V7 +
                            wine$V8 + wine$V9 + wine$V10 + wine$V11 + wine$V12 + wine$V13 +
                            wine$V14)
</pre>
 
<h3>Loadings for the Discriminant Functions</h3>
<p>To get the values of the loadings of the discriminant functions for the wine data, we can type:</p>
<pre>
&gt; wine.lda
  Coefficients of linear discriminants:
              LD1           LD2
  wine$V2  -0.403399781  0.8717930699
  wine$V3   0.165254596  0.3053797325
  wine$V4  -0.369075256  2.3458497486
  wine$V5   0.154797889 -0.1463807654
  wine$V6  -0.002163496 -0.0004627565
  wine$V7   0.618052068 -0.0322128171
  wine$V8  -1.661191235 -0.4919980543
  wine$V9  -1.495818440 -1.6309537953
  wine$V10  0.134092628 -0.3070875776
  wine$V11  0.355055710  0.2532306865
  wine$V12 -0.818036073 -1.5156344987
  wine$V13 -1.157559376  0.0511839665
  wine$V14 -0.002691206  0.0028529846
</pre>
<p>This means that the first discriminant function is a linear combination of the variables:
-0.403*V2 - 0.165*V3 - 0.369*V4 + 0.155*V5 - 0.002*V6 + 0.618*V7 - 1.661*V8
- 1.496*V9 + 0.134*V10 + 0.355*V11 - 0.818*V12 - 1.158*V13 - 0.003*V14, where
V2, V3, ... V14 are the concentrations of the 14 chemicals found in the wine samples.
For convenience, the value for each discriminant function (eg. the first discriminant function)
are scaled so that their mean value is zero (see below).</p>
<p>Note that these loadings are calculated so that the within-group variance of each discriminant
function for each group (cultivar) is equal to 1, as will be demonstrated below.</p>
<p>These scalings are also stored in the named element "scaling" of the variable returned
by the lda() function. This element contains a matrix, in which the first column contains
the loadings for the first discriminant function, the second column contains the loadings
for the second discriminant function and so on. For example, to extract the loadings for
the first discriminant function, we can type:</p>
<pre>
&gt; wine.lda$scaling[,1]
   wine$V2      wine$V3      wine$V4      wine$V5      wine$V6      wine$V7
 -0.403399781  0.165254596 -0.369075256  0.154797889 -0.002163496  0.618052068
   wine$V8      wine$V9     wine$V10     wine$V11     wine$V12     wine$V13
 -1.661191235 -1.495818440  0.134092628  0.355055710 -0.818036073 -1.157559376
  wine$V14
 -0.002691206
</pre>
<p>To calculate the values of the first discriminant function, we can define our own function "calclda()":</p>
<pre>
&gt; calclda &lt;- function(variables,loadings)
  {
     # find the number of samples in the data set
     as.data.frame(variables)
     numsamples &lt;- nrow(variables)
     # make a vector to store the discriminant function
     ld &lt;- numeric(numsamples)
     # find the number of variables
     numvariables &lt;- length(variables)
     # calculate the value of the discriminant function for each sample
     for (i in 1:numsamples)
     {
        valuei &lt;- 0
        for (j in 1:numvariables)
        {
           valueij &lt;- variables[i,j]
           loadingj &lt;- loadings[j]
           valuei &lt;- valuei + (valueij * loadingj)
        }
        ld[i] &lt;- valuei
     }
     # standardise the discriminant function so that its mean value is 0:
     ld &lt;- as.data.frame(scale(ld, center=TRUE, scale=FALSE))
     ld &lt;- ld[[1]]
     return(ld)
  }
</pre>
<p>The function calclda() simply calculates the value of a discriminant function
for each sample in the data set, for example, for the first disriminant function, for each sample we calculate
the value using the equation -0.403*V2 - 0.165*V3 - 0.369*V4 + 0.155*V5 - 0.002*V6 + 0.618*V7 - 1.661*V8
- 1.496*V9 + 0.134*V10 + 0.355*V11 - 0.818*V12 - 1.158*V13 - 0.003*V14. Furthermore, the "scale()"
command is used within the calclda() function in order to standardise the value of a discriminant function
(eg. the first discriminant function) so that its mean value (over all the wine samples) is 0.</p>
<p>We can use the function calclda() to calculate the values of the first discriminant function for each sample in our
wine data:</p>
<pre>
&gt; calclda(wine[2:14], wine.lda$scaling[,1])
  [1] -4.70024401 -4.30195811 -3.42071952 -4.20575366 -1.50998168 -4.51868934
  [7] -4.52737794 -4.14834781 -3.86082876 -3.36662444 -4.80587907 -3.42807646
  [13] -3.66610246 -5.58824635 -5.50131449 -3.18475189 -3.28936988 -2.99809262
  [19] -5.24640372 -3.13653106 -3.57747791 -1.69077135 -4.83515033 -3.09588961
  [25] -3.32164716 -2.14482223 -3.98242850 -2.68591432 -3.56309464 -3.17301573
  [31] -2.99626797 -3.56866244 -3.38506383 -3.52753750 -2.85190852 -2.79411996
  ...
</pre>
<p>In fact, the values of the first linear discriminant function can be calculated using the
"predict()" function in R, so we can compare those to the ones that we calculated, and they
should agree:</p>
<pre>
&gt; wine.lda.values &lt;- predict(wine.lda, wine[2:14])
&gt; wine.lda.values$x[,1] # contains the values for the first discriminant function
      1           2           3           4           5           6
  -4.70024401 -4.30195811 -3.42071952 -4.20575366 -1.50998168 -4.51868934
      7           8           9          10          11          12
  -4.52737794 -4.14834781 -3.86082876 -3.36662444 -4.80587907 -3.42807646
     13          14          15          16          17          18
  -3.66610246 -5.58824635 -5.50131449 -3.18475189 -3.28936988 -2.99809262
     19          20          21          22          23          24
  -5.24640372 -3.13653106 -3.57747791 -1.69077135 -4.83515033 -3.09588961
     25          26          27          28          29          30
  -3.32164716 -2.14482223 -3.98242850 -2.68591432 -3.56309464 -3.17301573
     31          32          33          34          35          36
  -2.99626797 -3.56866244 -3.38506383 -3.52753750 -2.85190852 -2.79411996
  ...
</pre>
<p>We see that they do agree.</p>
<p>It doesn't matter whether the input variables for linear discriminant analysis are standardised or not, unlike
for principal components analysis in which it is often necessary to standardise the input variables.
However, using standardised variables in linear discriminant analysis makes it easier to interpret the loadings in
a linear discriminant function.</p>
<p>In linear discriminant analysis, the standardised version of an input variable is defined so that it
has mean zero and within-groups variance of 1. Thus, we can calculate the "group-standardised" variable
by subtracting the mean from each value of the variable, and dividing by the within-groups standard deviation.
To calculate the group-standardised version of a set of variables, we can use the function "groupStandardise()" below:</p>
<pre>
&gt; groupStandardise &lt;- function(variables, groupvariable)
  {
     # find out how many variables we have
     variables &lt;- as.data.frame(variables)
     numvariables &lt;- length(variables)
     # find the variable names
     variablenames &lt;- colnames(variables)
     # calculate the group-standardised version of each variable
     for (i in 1:numvariables)
     {
        variablei &lt;- variables[i]
        variablei_name &lt;- variablenames[i]
        variablei_Vw &lt;- calcWithinGroupsVariance(variablei, groupvariable)
        variablei_mean &lt;- mean(variablei)
        variablei_new &lt;- (variablei - variablei_mean)/(sqrt(variablei_Vw))
        data_length &lt;- nrow(variablei)
        if (i == 1) { variables_new &lt;- data.frame(row.names=seq(1,data_length)) }
        variables_new[`variablei_name`] &lt;- variablei_new
     }
     return(variables_new)
  }
</pre>
<p>For example, we can use the "groupStandardise()" function to calculate the group-standardised versions of the
chemical concentrations in wine samples:</p>
<pre>
&gt; groupstandardisedconcentrations &lt;- groupStandardise(wine[2:14], wine[1])
</pre>
<p>We can then use the lda() function to perform linear disriminant analysis on the group-standardised variables:</p>
<pre>
&gt; wine.lda2 &lt;- lda(wine$V1 ~ groupstandardisedconcentrations$V2 + groupstandardisedconcentrations$V3 +
                             groupstandardisedconcentrations$V4 + groupstandardisedconcentrations$V5 +
                             groupstandardisedconcentrations$V6 + groupstandardisedconcentrations$V7 +
                             groupstandardisedconcentrations$V8 + groupstandardisedconcentrations$V9 +
                             groupstandardisedconcentrations$V10 + groupstandardisedconcentrations$V11 +
                             groupstandardisedconcentrations$V12 + groupstandardisedconcentrations$V13 +
                             groupstandardisedconcentrations$V14)
&gt; wine.lda2
  Coefficients of linear discriminants:
                                            LD1          LD2
  groupstandardisedconcentrations$V2  -0.20650463  0.446280119
  groupstandardisedconcentrations$V3   0.15568586  0.287697336
  groupstandardisedconcentrations$V4  -0.09486893  0.602988809
  groupstandardisedconcentrations$V5   0.43802089 -0.414203541
  groupstandardisedconcentrations$V6  -0.02907934 -0.006219863
  groupstandardisedconcentrations$V7   0.27030186 -0.014088108
  groupstandardisedconcentrations$V8  -0.87067265 -0.257868714
  groupstandardisedconcentrations$V9  -0.16325474 -0.178003512
  groupstandardisedconcentrations$V10  0.06653116 -0.152364015
  groupstandardisedconcentrations$V11  0.53670086  0.382782544
  groupstandardisedconcentrations$V12 -0.12801061 -0.237174509
  groupstandardisedconcentrations$V13 -0.46414916  0.020523349
  groupstandardisedconcentrations$V14 -0.46385409  0.491738050
</pre>
<p>It makes sense to interpret the loadings calculated using the group-standardised variables rather than the loadings for
the original (unstandardised) variables.</p>
<p>In the first discriminant function calculated for the group-standardised variables, the largest loadings (in absolute) value
are given to V8 (-0.871), V11 (0.537), V13 (-0.464), V14 (-0.464), and V5 (0.438). The loadings for V8, V13 and V14 are negative, while
those for V11 and V5 are positive. Therefore, the discriminant function seems to represent a contrast between the concentrations of
V8, V13 and V14, and the concentrations of V11 and V5.</p>
<p>We saw above that the individual variables which gave the greatest separations between the groups were V8 (separation 233.93), V14 (207.92),
V13 (189.97), V2 (135.08) and V11 (120.66). These were mostly the same variables that had the largest loadings in the linear discriminant
function (loading for V8: -0.871, for V14: -0.464, for V13: -0.464, for V11: 0.537).</p>
<p>We found above that variables V8 and V11 have a negative between-groups covariance (-60.41) and a positive within-groups covariance (0.29).
When the between-groups covariance and within-groups covariance for two variables have opposite signs, it indicates that a better separation
between groups can be obtained by using a linear combination of those two variables than by using either variable on its own.</p>
<p>Thus, given that the two variables V8 and V11 have between-groups and within-groups covariances of opposite signs, and that these are two
of the variables that gave the greatest separations between groups when used individually, it is not surprising that these are the two
variables that have the largest loadings in the first discriminant function.</p>
<p>Note that although the loadings for the group-standardised variables are easier to interpret than the loadings for the
unstandardised variables, the values of the discriminant function are the same regardless of whether we standardise
the input variables or not. For example, for wine data, we can calculate the value of the first discriminant function calculated
using the unstandardised and group-standardised variables by typing:</p>
<pre>
&gt; wine.lda.values &lt;- predict(wine.lda, wine[2:14])
&gt; wine.lda.values$x[,1] # values for the first discriminant function, using the unstandardised data
      1           2           3           4           5           6
  -4.70024401 -4.30195811 -3.42071952 -4.20575366 -1.50998168 -4.51868934
      7           8           9          10          11          12
  -4.52737794 -4.14834781 -3.86082876 -3.36662444 -4.80587907 -3.42807646
     13          14          15          16          17          18
  -3.66610246 -5.58824635 -5.50131449 -3.18475189 -3.28936988 -2.99809262
     19          20          21          22          23          24
  -5.24640372 -3.13653106 -3.57747791 -1.69077135 -4.83515033 -3.09588961
  ...
&gt; wine.lda.values2 &lt;- predict(wine.lda2, groupstandardisedconcentrations)
&gt; wine.lda.values2$x[,1] # values for the first discriminant function, using the standardised data
      1           2           3           4           5           6
  -4.70024401 -4.30195811 -3.42071952 -4.20575366 -1.50998168 -4.51868934
      7           8           9          10          11          12
  -4.52737794 -4.14834781 -3.86082876 -3.36662444 -4.80587907 -3.42807646
     13          14          15          16          17          18
  -3.66610246 -5.58824635 -5.50131449 -3.18475189 -3.28936988 -2.99809262
     19          20          21          22          23          24
  -5.24640372 -3.13653106 -3.57747791 -1.69077135 -4.83515033 -3.09588961
  ...
</pre>
<p>We can see that although the loadings are different for the first discriminant functions calculated using
unstandardised and group-standardised data, the actual values of the first discriminant function are the same.</p>
 
 
<h3>Separation Achieved by the Discriminant Functions</h3>
<p>To calculate the separation achieved by each discriminant function, we first need to calculate the
value of each discriminant function, by substituting the variables' values into the linear combination for
the discriminant function (eg. -0.403*V2 - 0.165*V3 - 0.369*V4 + 0.155*V5 - 0.002*V6 + 0.618*V7 - 1.661*V8
- 1.496*V9 + 0.134*V10 + 0.355*V11 - 0.818*V12 - 1.158*V13 - 0.003*V14 for the first discriminant function),
and then scaling the values of the discriminant function so that their mean is zero.</p>
<p>As mentioned above, we can do this using the "predict()" function in R. For example,
to calculate the value of the discriminant functions for the wine data, we type:</p>
<pre>
&gt; wine.lda.values &lt;- predict(wine.lda, standardisedconcentrations)
</pre>
<p>The returned variable has a named element "x" which is a matrix containing the linear discriminant functions:
the first column of x contains the first discriminant function, the second column of x contains the second
discriminant function, and so on (if there are more discriminant functions).</p>
<p>We can therefore calculate the separations achieved by the two linear discriminant functions for the wine data by using the
"calcSeparations()" function (see above), which calculates the separation as the ratio of the between-groups
variance to the within-groups variance:</p>
<pre>
&gt; calcSeparations(wine.lda.values$x,wine[1])
  [1] "variable LD1 Vw= 1 Vb= 794.652200566216 separation= 794.652200566216"
  [1] "variable LD2 Vw= 1 Vb= 361.241041493455 separation= 361.241041493455"
</pre>
<p>As mentioned above, the loadings for each discriminant function are calculated in such a way that
the within-group variance (Vw) for each group (wine cultivar here) is equal to 1, as we see in the
output from calcSeparations() above.</p>
<p>The output from calcSeparations() tells us that the separation achieved by the first (best) discriminant
function is 794.7, and the separation achieved by the second (second best) discriminant function is 361.2.</p>
<p>Therefore, the total separation is the sum of these, which is (794.652200566216+361.241041493455=1155.893)
1155.89, rounded to two decimal places. Therefore, the "percentage separation" achieved by the
first discriminant function is (794.652200566216*100/1155.893=) 68.75%, and the percentage separation achieved by the
second discriminant function is (361.241041493455*100/1155.893=) 31.25%.</p>
<p>The "proportion of trace" that is printed when you type "wine.lda" (the variable returned by the lda() function)
is the percentage separation achieved by each discriminant function. For example, for the wine data we get the
same values as just calculated (68.75% and 31.25%):</p>
<pre>
&gt; wine.lda
  Proportion of trace:
    LD1    LD2
  0.6875 0.3125
</pre>
<p>Therefore, the first discriminant function does achieve a good separation between the three groups (three cultivars), but the second
discriminant function does improve the separation of the groups by quite a large amount, so is it worth using the
second discriminant function as well. Therefore, to achieve a good separation of the groups (cultivars),
it is necessary to use both of the first two discriminant functions.</p>
<p>We found above that the largest separation achieved for any of the individual variables (individual chemical concentrations)
was 233.9 for V8, which is quite a lot less than 794.7, the separation achieved by the first discriminant function. Therefore,
the effect of using more than one variable to calculate the discriminant function is that we can find a discriminant function
that achieves a far greater separation between groups than achieved by any one variable alone.</p>
<p>The variable returned by the lda() function also has a named element "svd", which contains the ratio of
between- and within-group standard deviations for the linear discriminant variables, that is, the square
root of the "separation" value that we calculated using calcSeparations() above. When we calculate the
square of the value stored in "svd", we should get the same value as found using calcSeparations():</p>
<pre>
&gt; (wine.lda$svd)^2
  [1] 794.6522 361.2410
</pre>
 
 
<h3>A Stacked Histogram of the LDA Values</h3>
<p>A nice way of displaying the results of a linear discriminant analysis (LDA) is to make a stacked histogram of the
values of the discriminant function for the samples from different groups (different wine cultivars in our example).</p>
<p>We can do this using the "ldahist()" function in R. For example, to make a stacked histogram of the first discriminant
function's values for wine samples of the three different wine cultivars, we type:</p>
<pre>
&gt; ldahist(data = wine.lda.values$x[,1], g=wine$V1)
</pre>
<p><img alt="image8" src="../_static/image8.png"></p>
<p>We can see from the histogram that cultivars 1 and 3 are well separated by the first
discriminant function, since the values for the first cultivar are between -6 and -1,
while the values for cultivar 3 are between 2 and 6, and so there is no overlap in values.</p>
<p>However, the separation achieved by the linear discriminant function on the training
set may be an overestimate. To get a more accurate idea of how well the first discriminant function
separates the groups, we would need to see a stacked histogram of the values for the three
cultivars using some unseen "test set", that is, using
a set of data that was not used to calculate the linear discriminant function.</p>
<p>We see that the first discriminant function separates cultivars 1 and 3 very well, but
does not separate cultivars 1 and 2, or cultivars 2 and 3, so well.</p>
<p>We therefore investigate whether the second discriminant function separates those cultivars,
by making a stacked histogram of the second discriminant function's values:</p>
<pre>
&gt; ldahist(data = wine.lda.values$x[,2], g=wine$V1)
</pre>
<p><img alt="image9" src="../_static/image9.png"></p>
<p>We see that the second discriminant function separates cultivars 1 and 2 quite well, although
there is a little overlap in their values. Furthermore, the second discriminant function also
separates cultivars 2 and 3 quite well, although again there is a little overlap in their values so
it is not perfect.</p>
<p>Thus, we see that two discriminant functions are necessary to separate the cultivars, as was
discussed above (see the discussion of percentage separation above).</p>
 
 
<h3>Scatterplots of the Discriminant Functions</h3>
<p>We can obtain a scatterplot of the best two discriminant functions, with the data points labelled by cultivar, by typing:</p>
<pre>
&gt; plot(wine.lda.values$x[,1],wine.lda.values$x[,2]) # make a scatterplot
&gt; text(wine.lda.values$x[,1],wine.lda.values$x[,2],wine$V1,cex=0.7,pos=4,col="red") # add labels
</pre>
<p><img alt="image10" src="../_static/image10.png"></p>
<p>From the scatterplot of the first two discriminant functions, we can see that the wines from the three
cultivars are well separated in the scatterplot. The first discriminant function (x-axis)
separates cultivars 1 and 3 very well, but doesn't not perfectly separate cultivars
1 and 3, or cultivars 2 and 3.</p>
<p>The second discriminant function (y-axis) achieves a fairly good separation of cultivars
1 and 3, and cultivars 2 and 3, although it is not totally perfect.</p>
<p>To achieve a very good separation of the three cultivars, it would be best to use both the first and second
discriminant functions together, since the first discriminant function can separate cultivars 1 and 3 very well,
and the second discriminant function can separate cultivars 1 and 2, and cultivars 2 and 3, reasonably well.</p>
 
 
<h3>Allocation Rules and Misclassification Rate</h3>
<p>We can calculate the mean values of the discriminant functions for each of the three cultivars using the
"printMeanAndSdByGroup()" function (see above):</p>
<pre>
&gt; printMeanAndSdByGroup(wine.lda.values$x,wine[1])
  [1] "Group 1 Means:"
     LD1       LD2
  -3.422489  1.691674
  [1] "Group 2 Means:"
     LD1         LD2
  -0.07972623 -2.47265573
  [1] "Group 3 Means:"
     LD1      LD2
  4.324737 1.578120
</pre>
<p>We find that the mean value of the first discriminant function is -3.422489 for cultivar 1, -0.07972623 for cultivar 2,
and 4.324737 for cultivar 3. The mid-way point between the mean values for cultivars 1 and 2 is (-3.422489-0.07972623)/2=-1.751108,
and the mid-way point between the mean values for cultivars 2 and 3 is (-0.07972623+4.324737)/2 = 2.122505.</p>
<p>Therefore, we can use the following allocation rule:</p>
<ul>
<li>if the first discriminant function is &lt;= -1.751108, predict the sample to be from cultivar 1</li>
<li>if the first discriminant function is &gt; -1.751108 and &lt;= 2.122505, predict the sample to be from cultivar 2</li>
<li>if the first discriminant function is &gt; 2.122505, predict the sample to be from cultivar 3</li>
</ul><p>We can examine the accuracy of this allocation rule by using the "calcAllocationRuleAccuracy()" function below:</p>
<pre>
&gt; calcAllocationRuleAccuracy &lt;- function(ldavalue, groupvariable, cutoffpoints)
  {
     # find out how many values the group variable can take
     groupvariable2 &lt;- as.factor(groupvariable[[1]])
     levels &lt;- levels(groupvariable2)
     numlevels &lt;- length(levels)
     # calculate the number of true positives and false negatives for each group
     numlevels &lt;- length(levels)
     for (i in 1:numlevels)
     {
        leveli &lt;- levels[i]
        levelidata &lt;- ldavalue[groupvariable==leveli]
        # see how many of the samples from this group are classified in each group
        for (j in 1:numlevels)
        {
           levelj &lt;- levels[j]
           if (j == 1)
           {
              cutoff1 &lt;- cutoffpoints[1]
              cutoff2 &lt;- "NA"
              results &lt;- summary(levelidata &lt;= cutoff1)
           }
           else if (j == numlevels)
           {
              cutoff1 &lt;- cutoffpoints[(numlevels-1)]
              cutoff2 &lt;- "NA"
              results &lt;- summary(levelidata &gt; cutoff1)
           }
           else
           {
              cutoff1 &lt;- cutoffpoints[(j-1)]
              cutoff2 &lt;- cutoffpoints[(j)]
              results &lt;- summary(levelidata &gt; cutoff1 &amp; levelidata &lt;= cutoff2)
           }
           trues &lt;- results["TRUE"]
           trues &lt;- trues[[1]]
           print(paste("Number of samples of group",leveli,"classified as group",levelj," : ",
              trues,"(cutoffs:",cutoff1,",",cutoff2,")"))
        }
     }
  }
</pre>
<p>For example, to calculate the accuracy for the wine data based on the allocation
rule for the first discriminant function, we type:</p>
<pre>
&gt; calcAllocationRuleAccuracy(wine.lda.values$x[,1], wine[1], c(-1.751108, 2.122505))
  [1] "Number of samples of group 1 classified as group 1  :  56 (cutoffs: -1.751108 , NA )"
  [1] "Number of samples of group 1 classified as group 2  :  3 (cutoffs: -1.751108 , 2.122505 )"
  [1] "Number of samples of group 1 classified as group 3  :  NA (cutoffs: 2.122505 , NA )"
  [1] "Number of samples of group 2 classified as group 1  :  5 (cutoffs: -1.751108 , NA )"
  [1] "Number of samples of group 2 classified as group 2  :  65 (cutoffs: -1.751108 , 2.122505 )"
  [1] "Number of samples of group 2 classified as group 3  :  1 (cutoffs: 2.122505 , NA )"
  [1] "Number of samples of group 3 classified as group 1  :  NA (cutoffs: -1.751108 , NA )"
  [1] "Number of samples of group 3 classified as group 2  :  NA (cutoffs: -1.751108 , 2.122505 )"
  [1] "Number of samples of group 3 classified as group 3  :  48 (cutoffs: 2.122505 , NA )"
</pre>
<p>This can be displayed in a "confusion matrix":</p>
<table border="1">
<tr>
<th> </th>
<th>Allocated to group 1</th>
<th>Allocated to group 2</th>
<th>Allocated to group 3</th>
</tr>
<tr>
<td>Is group 1</td>
<td>56</td>
<td>3</td>
<td>0</td>
</tr>
<tr>
<td>Is group 2</td>
<td>5</td>
<td>65</td>
<td>1</td>
</tr>
<tr>
<td>Is group 3</td>
<td>0</td>
<td>0</td>
<td>48</td>
</tr>
</table><p>There are 3+5+1=9 wine samples that are misclassified, out of (56+3+5+65+1+48=) 178 wine samples:
3 samples from cultivar 1 are predicted to be from cultivar 2, 5 samples from cultivar 2 are predicted
to be from cultivar 1, and 1 sample from cultivar 2 is predicted to be from cultivar 3.
Therefore, the misclassification rate is 9/178, or 5.1%. The misclassification rate is quite low,
and therefore the accuracy of the allocation rule appears to be relatively high.</p>
<p>However, this is probably an underestimate of the misclassification rate, as the allocation rule was based on this data (this is
the "training set"). If we calculated the misclassification rate for a separate "test set" consisting of data other than that
used to make the allocation rule, we would probably get a higher estimate of the misclassification rate.</p>
 
 
 
<h2>Links and Further Reading</h2>
<p>Here are some links for further reading.</p>
<p>For a more in-depth introduction to R, a good online tutorial is
available on the "Kickstarting R" website,
<a href="http://cran.r-project.org/doc/contrib/Lemon-kickstart/">cran.r-project.org/doc/contrib/Lemon-kickstart</a>.</p>
<p>There is another nice (slightly more in-depth) tutorial to R
available on the "Introduction to R" website,
<a href="http://cran.r-project.org/doc/manuals/R-intro.html">cran.r-project.org/doc/manuals/R-intro.html</a>.</p>
<p>To learn about multivariate analysis, I would highly recommend the book "Multivariate
analysis" (product code M249/03) by the Open University, available from <a href="http://www.ouw.co.uk/store/">the Open University Shop</a>.</p>
<p>There is a book available in the "Use R!" series on using R for multivariate analyses,
<a href="http://www.springer.com/statistics/statistical+theory+and+methods/book/978-1-4419-9649-7">An Introduction to Applied Multivariate Analysis with R</a>
by Everitt and Hothorn.</p>
 
 
<h2>Acknowledgements</h2>
<p>Many of the examples in this booklet are inspired by examples in the excellent Open University book,
"Multivariate Analysis" (product code M249/03),
available from <a href="http://www.ouw.co.uk/store/">the Open University Shop</a>.</p>
<p>I am grateful to the UCI Machine Learning Repository,
<a href="http://archive.ics.uci.edu/ml">http://archive.ics.uci.edu/ml</a>, for making data sets available
which I have used in the examples in this booklet.</p>
 
 
<h2>Contact</h2>
<p>I will be grateful if you will send me (<a href="http://www.ucc.ie/microbio/avrilcoghlan/">Avril Coghlan</a>) corrections or suggestions for improvements to
my email address <a href="mailto:a.coghlan%40ucc.ie">a.coghlan@ucc.ie</a></p>
 
 
<h2>License</h2>
<p>The content in this book is licensed under a <a href="http://creativecommons.org/licenses/by/3.0/">Creative Commons Attribution 3.0 License</a>.</p>
 
 
 </div>
  </div>


          </div>
        </div>
      </div>
    </div>
  

  </div>


<div class="frame frame-loading" style="display:none;" data-tree-list-url="/avrilcoghlan/LittleBookofRMultivariateAnalysis/tree-list/781a1ba06b3c4a367dc3e368cedce5a429954c76" data-blob-url-prefix="/avrilcoghlan/LittleBookofRMultivariateAnalysis/blob/781a1ba06b3c4a367dc3e368cedce5a429954c76">
  <img src="https://a248.e.akamai.net/assets.github.com/images/modules/ajax/big_spinner_336699.gif" height="32" width="32">
</div>

    </div>
  
      
    </div>

    <!--**************
     FOOTER
     **************-->
    <div id="footer" >
      <div class="upper_footer">
        <div class="site" class="clearfix">

        <!--[if IE]><h4 id="blacktocat_ie">GitHub Links</h4><![endif]-->
        <![if !IE]><h4 id="blacktocat">GitHub Links</h4><![endif]>

        <ul class="footer_nav">
          <h4>GitHub</h4>
          <li><a href="https://github.com/about">About</a></li>
          <li><a href="https://github.com/blog">Blog</a></li>
          <li><a href="https://github.com/features">Features</a></li>
          <li><a href="https://github.com/contact">Contact &amp; Support</a></li>
          <li><a href="https://github.com/training">Training</a></li>
          <li><a href="http://status.github.com/">Site Status</a></li>
        </ul>

        <ul class="footer_nav">
          <h4>Tools</h4>
          <li><a href="http://mac.github.com/">GitHub for Mac</a></li>
          <li><a href="http://mobile.github.com/">Issues for iPhone</a></li>
          <li><a href="https://gist.github.com">Gist: Code Snippets</a></li>
          <li><a href="http://fi.github.com/">Enterprise Install</a></li>
          <li><a href="http://jobs.github.com/">Job Board</a></li>
        </ul>

        <ul class="footer_nav">
          <h4>Extras</h4>
          <li><a href="http://shop.github.com/">GitHub Shop</a></li>
          <li><a href="http://octodex.github.com/">The Octodex</a></li>
        </ul>

        <ul class="footer_nav">
          <h4>Documentation</h4>
          <li><a href="http://help.github.com/">GitHub Help</a></li>
          <li><a href="http://developer.github.com/">Developer API</a></li>
          <li><a href="http://github.github.com/github-flavored-markdown/">GitHub Flavored Markdown</a></li>
          <li><a href="http://pages.github.com/">GitHub Pages</a></li>
        </ul>

        </div><!-- /.site -->
      </div><!-- /.upper_footer -->

      <div class="lower_footer">
        <div class="site" class="clearfix">

        <!--[if IE]><div id="legal_ie"><![endif]-->
        <![if !IE]><div id="legal"><![endif]>
              
              <ul>
                <li><a href="https://github.com/site/terms">Terms of Service</a></li>
                <li><a href="https://github.com/site/privacy">Privacy</a></li>
                <li><a href="https://github.com/security">Security</a></li>
              </ul>
              

              <p>&copy; 2011 <span id="_rrt" title="0.06745s from fe7.rs.github.com">GitHub</span> Inc. All rights reserved.</p>
            </div><!-- /#legal or /#legal_ie-->

          
          <div class="sponsor">
              <a href="http://www.rackspace.com" class="logo">
                <img alt="Dedicated Server" height="36" src="https://a248.e.akamai.net/assets.github.com/images/modules/footer/rackspace_logo.png?v2" width="38" />
              </a>
              Powered by the <a href="http://www.rackspace.com ">Dedicated
              Servers</a> and<br/> <a href="http://www.rackspacecloud.com">Cloud
              Computing</a> of Rackspace Hosting<span>&reg;</span>
          </div>
          
        </div><!-- /.site -->
      </div><!-- /.lower_footer -->
    </div><!-- /#footer -->

    

<div id="keyboard_shortcuts_pane" class="instapaper_ignore readability-extra" style="display:none">
  <h2>Keyboard Shortcuts <small><a href="#" class="js-see-all-keyboard-shortcuts">(see all)</a></small></h2>

  <div class="columns threecols">
    <div class="column first">
      <h3>Site wide shortcuts</h3>
      <dl class="keyboard-mappings">
        <dt>s</dt>
        <dd>Focus site search</dd>
      </dl>
      <dl class="keyboard-mappings">
        <dt>?</dt>
        <dd>Bring up this help dialog</dd>
      </dl>
    </div><!-- /.column.first -->

    <div class="column middle" style='display:none'>
      <h3>Commit list</h3>
      <dl class="keyboard-mappings">
        <dt>j</dt>
        <dd>Move selected down</dd>
      </dl>
      <dl class="keyboard-mappings">
        <dt>k</dt>
        <dd>Move selected up</dd>
      </dl>
      <dl class="keyboard-mappings">
        <dt>c <em>or</em> o <em>or</em> enter</dt>
        <dd>Open commit</dd>
      </dl>
      <dl class="keyboard-mappings">
        <dt>y</dt>
        <dd>Expand URL to its canonical form</dd>
      </dl>
    </div><!-- /.column.first -->

    <div class="column last" style='display:none'>
      <h3>Pull request list</h3>
      <dl class="keyboard-mappings">
        <dt>j</dt>
        <dd>Move selected down</dd>
      </dl>
      <dl class="keyboard-mappings">
        <dt>k</dt>
        <dd>Move selected up</dd>
      </dl>
      <dl class="keyboard-mappings">
        <dt>o <em>or</em> enter</dt>
        <dd>Open issue</dd>
      </dl>
    </div><!-- /.columns.last -->

  </div><!-- /.columns.equacols -->

  <div style='display:none'>
    <div class="rule"></div>

    <h3>Issues</h3>

    <div class="columns threecols">
      <div class="column first">
        <dl class="keyboard-mappings">
          <dt>j</dt>
          <dd>Move selected down</dd>
        </dl>
        <dl class="keyboard-mappings">
          <dt>k</dt>
          <dd>Move selected up</dd>
        </dl>
        <dl class="keyboard-mappings">
          <dt>x</dt>
          <dd>Toggle select target</dd>
        </dl>
        <dl class="keyboard-mappings">
          <dt>o <em>or</em> enter</dt>
          <dd>Open issue</dd>
        </dl>
      </div><!-- /.column.first -->
      <div class="column middle">
        <dl class="keyboard-mappings">
          <dt>I</dt>
          <dd>Mark selected as read</dd>
        </dl>
        <dl class="keyboard-mappings">
          <dt>U</dt>
          <dd>Mark selected as unread</dd>
        </dl>
        <dl class="keyboard-mappings">
          <dt>e</dt>
          <dd>Close selected</dd>
        </dl>
        <dl class="keyboard-mappings">
          <dt>y</dt>
          <dd>Remove selected from view</dd>
        </dl>
      </div><!-- /.column.middle -->
      <div class="column last">
        <dl class="keyboard-mappings">
          <dt>c</dt>
          <dd>Create issue</dd>
        </dl>
        <dl class="keyboard-mappings">
          <dt>l</dt>
          <dd>Create label</dd>
        </dl>
        <dl class="keyboard-mappings">
          <dt>i</dt>
          <dd>Back to inbox</dd>
        </dl>
        <dl class="keyboard-mappings">
          <dt>u</dt>
          <dd>Back to issues</dd>
        </dl>
        <dl class="keyboard-mappings">
          <dt>/</dt>
          <dd>Focus issues search</dd>
        </dl>
      </div>
    </div>
  </div>

  <div style='display:none'>
    <div class="rule"></div>

    <h3>Network Graph</h3>
    <div class="columns equacols">
      <div class="column first">
        <dl class="keyboard-mappings">
          <dt><span class="badmono">←</span> <em>or</em> h</dt>
          <dd>Scroll left</dd>
        </dl>
        <dl class="keyboard-mappings">
          <dt><span class="badmono">→</span> <em>or</em> l</dt>
          <dd>Scroll right</dd>
        </dl>
        <dl class="keyboard-mappings">
          <dt><span class="badmono">↑</span> <em>or</em> k</dt>
          <dd>Scroll up</dd>
        </dl>
        <dl class="keyboard-mappings">
          <dt><span class="badmono">↓</span> <em>or</em> j</dt>
          <dd>Scroll down</dd>
        </dl>
        <dl class="keyboard-mappings">
          <dt>t</dt>
          <dd>Toggle visibility of head labels</dd>
        </dl>
      </div><!-- /.column.first -->
      <div class="column last">
        <dl class="keyboard-mappings">
          <dt>shift <span class="badmono">←</span> <em>or</em> shift h</dt>
          <dd>Scroll all the way left</dd>
        </dl>
        <dl class="keyboard-mappings">
          <dt>shift <span class="badmono">→</span> <em>or</em> shift l</dt>
          <dd>Scroll all the way right</dd>
        </dl>
        <dl class="keyboard-mappings">
          <dt>shift <span class="badmono">↑</span> <em>or</em> shift k</dt>
          <dd>Scroll all the way up</dd>
        </dl>
        <dl class="keyboard-mappings">
          <dt>shift <span class="badmono">↓</span> <em>or</em> shift j</dt>
          <dd>Scroll all the way down</dd>
        </dl>
      </div><!-- /.column.last -->
    </div>
  </div>

  <div >
    <div class="rule"></div>
    <div class="columns threecols">
      <div class="column first" >
        <h3>Source Code Browsing</h3>
        <dl class="keyboard-mappings">
          <dt>t</dt>
          <dd>Activates the file finder</dd>
        </dl>
        <dl class="keyboard-mappings">
          <dt>l</dt>
          <dd>Jump to line</dd>
        </dl>
        <dl class="keyboard-mappings">
          <dt>y</dt>
          <dd>Expand URL to its canonical form</dd>
        </dl>
      </div>
    </div>
  </div>
</div>

    <div id="markdown-help" class="instapaper_ignore readability-extra">
  <h2>Markdown Cheat Sheet</h2>

  <div class="cheatsheet-content">

  <div class="mod">
    <div class="col">
      <h3>Format Text</h3>
      <p>Headers</p>
      <pre>
# This is an &lt;h1&gt; tag
## This is an &lt;h2&gt; tag
###### This is an &lt;h6&gt; tag</pre>
     <p>Text styles</p>
     <pre>
*This text will be italic*
_This will also be italic_
**This text will be bold**
__This will also be bold__

*You **can** combine them*
</pre>
    </div>
    <div class="col">
      <h3>Lists</h3>
      <p>Unordered</p>
      <pre>
* Item 1
* Item 2
  * Item 2a
  * Item 2b</pre>
     <p>Ordered</p>
     <pre>
1. Item 1
2. Item 2
3. Item 3
   * Item 3a
   * Item 3b</pre>
    </div>
    <div class="col">
      <h3>Miscellaneous</h3>
      <p>Images</p>
      <pre>
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)
</pre>
     <p>Links</p>
     <pre>
http://github.com - automatic!
[GitHub](http://github.com)</pre>
<p>Blockquotes</p>
     <pre>
As Kanye West said:
> We're living the future so
> the present is our past.
</pre>
    </div>
  </div>
  <div class="rule"></div>

  <h3>Code Examples in Markdown</h3>
  <div class="col">
      <p>Syntax highlighting with <a href="http://github.github.com/github-flavored-markdown/" title="GitHub Flavored Markdown" target="_blank">GFM</a></p>
      <pre>
```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```</pre>
    </div>
    <div class="col">
      <p>Or, indent your code 4 spaces</p>
      <pre>
Here is a Python code example
without syntax highlighting:

    def foo:
      if not bar:
        return true</pre>
    </div>
    <div class="col">
      <p>Inline code for comments</p>
      <pre>
I think you should use an
`&lt;addr&gt;` element here instead.</pre>
    </div>
  </div>

  </div>
</div>
    

    
    
    
    <script type="text/javascript">(function(){var d=document;var e=d.createElement("script");e.async=true;e.src="https://d1ros97qkrwjf5.cloudfront.net/16/eum/rum.js";e.type="text/javascript";var s=d.getElementsByTagName("script")[0];s.parentNode.insertBefore(e,s);})();NREUMQ.push(["nrf2","beacon-1.newrelic.com","2f94e4d8c2",64799,"dw1bEBZcX1RWRhoEClsAGhcMXEQ=",0,63,new Date().getTime()])</script>
  </body>
</html>

