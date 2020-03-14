





<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
  <link rel="dns-prefetch" href="https://github.githubassets.com">
  <link rel="dns-prefetch" href="https://avatars0.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars1.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars2.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars3.githubusercontent.com">
  <link rel="dns-prefetch" href="https://github-cloud.s3.amazonaws.com">
  <link rel="dns-prefetch" href="https://user-images.githubusercontent.com/">



  <link crossorigin="anonymous" media="all" integrity="sha512-5Bs4ERl99/u2AUfpOZF2F0cdfNby7+Vd9teUshXUBPo5CjwECR7IAEf+weI/eCk5tF7K1h3O8hd8k0+P/HePeg==" rel="stylesheet" href="https://github.githubassets.com/assets/frameworks-e41b3811197df7fbb60147e939917617.css" />
  
    <link crossorigin="anonymous" media="all" integrity="sha512-wQ0P70Gz4goIZNm3fW0Jh3dEzei2qCwCQfmYJrXxIORA/b2ybCT3OXSETvOpwvVVe+aPs8GO3p1n9ERgO6YfnQ==" rel="stylesheet" href="https://github.githubassets.com/assets/github-c10d0fef41b3e20a0864d9b77d6d0987.css" />
    
    
    
    


  <meta name="viewport" content="width=device-width">
  
  <title>Reproducible-Research-Course-Project-1/PA1_template.md at master · Natasha-R/Reproducible-Research-Course-Project-1</title>
    <meta name="description" content="Repository for Course Project 1 for the &quot;Reproducible Research&quot; Course on Coursera - Natasha-R/Reproducible-Research-Course-Project-1">
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
  <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
  <meta property="fb:app_id" content="1401488693436528">

    <meta name="twitter:image:src" content="https://avatars1.githubusercontent.com/u/12715753?s=400&amp;v=4" /><meta name="twitter:site" content="@github" /><meta name="twitter:card" content="summary" /><meta name="twitter:title" content="Natasha-R/Reproducible-Research-Course-Project-1" /><meta name="twitter:description" content="Repository for Course Project 1 for the &quot;Reproducible Research&quot; Course on Coursera - Natasha-R/Reproducible-Research-Course-Project-1" />
    <meta property="og:image" content="https://avatars1.githubusercontent.com/u/12715753?s=400&amp;v=4" /><meta property="og:site_name" content="GitHub" /><meta property="og:type" content="object" /><meta property="og:title" content="Natasha-R/Reproducible-Research-Course-Project-1" /><meta property="og:url" content="https://github.com/Natasha-R/Reproducible-Research-Course-Project-1" /><meta property="og:description" content="Repository for Course Project 1 for the &quot;Reproducible Research&quot; Course on Coursera - Natasha-R/Reproducible-Research-Course-Project-1" />

  <link rel="assets" href="https://github.githubassets.com/">
  <link rel="web-socket" href="wss://live.github.com/_sockets/VjI6NDk2MDE3OTg2OjIwZDA4ZGQ4NDI4ZTU4MzcxMGYxYzAxZTBlOGE0ZDUwZTc3MWMzMDk2OTQ3ZTBjMWE4MjM2ZDAwMDYwYWM3YTc=--a7cc4ef509d105b151833b7adb1d11fbcd7853e5">
  <link rel="sudo-modal" href="/sessions/sudo_modal">

  <meta name="request-id" content="CD9B:0E63:7FC43:A8963:5E692800" data-pjax-transient="true" /><meta name="html-safe-nonce" content="ff74d326edbdbbceb149db0a5e8ddc3eead29956" data-pjax-transient="true" /><meta name="visitor-payload" content="eyJyZWZlcnJlciI6Imh0dHBzOi8vZ2l0aHViLmNvbS9OYXRhc2hhLVIvUmVwcm9kdWNpYmxlLVJlc2VhcmNoLUNvdXJzZS1Qcm9qZWN0LTEiLCJyZXF1ZXN0X2lkIjoiQ0Q5QjowRTYzOjdGQzQzOkE4OTYzOjVFNjkyODAwIiwidmlzaXRvcl9pZCI6IjM5MjU1OTY3ODE1MjUxODMwOTAiLCJyZWdpb25fZWRnZSI6ImFwLXNvdXRoLTEiLCJyZWdpb25fcmVuZGVyIjoiaWFkIn0=" data-pjax-transient="true" /><meta name="visitor-hmac" content="e93863dd894cec4ad2d4aa4402036ee7f31bd82cde4922292a26a2572f03cf6c" data-pjax-transient="true" />



  <meta name="github-keyboard-shortcuts" content="repository,source-code" data-pjax-transient="true" />

  

  <meta name="selected-link" value="repo_source" data-pjax-transient>

      <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
    <meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
    <meta name="google-site-verification" content="GXs5KoUUkNCoaAZn7wPN-t01Pywp9M3sEjnt_3_ZWPc">

  <meta name="octolytics-host" content="collector.githubapp.com" /><meta name="octolytics-app-id" content="github" /><meta name="octolytics-event-url" content="https://collector.githubapp.com/github-external/browser_event" /><meta name="octolytics-dimension-ga_id" content="" class="js-octo-ga-id" /><meta name="octolytics-actor-id" content="60666183" /><meta name="octolytics-actor-login" content="akshitkashyap" /><meta name="octolytics-actor-hash" content="de7b2e1d0ad31a966f45661ce3946c4b33a1c51c816a2975954d804c0d9dab2d" />
<meta name="analytics-location" content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" />



    <meta name="google-analytics" content="UA-3769691-2">

  <meta class="js-ga-set" name="userId" content="9ff86654fbd9efa17129cc102d6485b4">

<meta class="js-ga-set" name="dimension1" content="Logged In">



  

      <meta name="hostname" content="github.com">
    <meta name="user-login" content="akshitkashyap">

      <meta name="expected-hostname" content="github.com">

      <meta name="js-proxy-site-detection-payload" content="ZjdhNWY0MjFmMzI0ZjE1NjljMTA0OGU3NGI0NDBmZGFmNmM2MTBmNGFmZDQyNzYzYWMzOTE5ZDZmODBjMDZmN3x7InJlbW90ZV9hZGRyZXNzIjoiMS4xODYuMTMuNiIsInJlcXVlc3RfaWQiOiJDRDlCOjBFNjM6N0ZDNDM6QTg5NjM6NUU2OTI4MDAiLCJ0aW1lc3RhbXAiOjE1ODM5NDk4MzEsImhvc3QiOiJnaXRodWIuY29tIn0=">

    <meta name="enabled-features" content="MARKETPLACE_FEATURED_BLOG_POSTS,MARKETPLACE_INVOICED_BILLING,MARKETPLACE_SOCIAL_PROOF_CUSTOMERS,MARKETPLACE_TRENDING_SOCIAL_PROOF,MARKETPLACE_RECOMMENDATIONS,MARKETPLACE_PENDING_INSTALLATIONS,RELATED_ISSUES,GHE_CLOUD_TRIAL,PAGE_STALE_CHECK">

  <meta http-equiv="x-pjax-version" content="57ebc598a31e18341d560370b4fc9bec">
  

      <link href="https://github.com/Natasha-R/Reproducible-Research-Course-Project-1/commits/master.atom" rel="alternate" title="Recent Commits to Reproducible-Research-Course-Project-1:master" type="application/atom+xml">

  <meta name="go-import" content="github.com/Natasha-R/Reproducible-Research-Course-Project-1 git https://github.com/Natasha-R/Reproducible-Research-Course-Project-1.git">

  <meta name="octolytics-dimension-user_id" content="12715753" /><meta name="octolytics-dimension-user_login" content="Natasha-R" /><meta name="octolytics-dimension-repository_id" content="42651708" /><meta name="octolytics-dimension-repository_nwo" content="Natasha-R/Reproducible-Research-Course-Project-1" /><meta name="octolytics-dimension-repository_public" content="true" /><meta name="octolytics-dimension-repository_is_fork" content="true" /><meta name="octolytics-dimension-repository_parent_id" content="16709733" /><meta name="octolytics-dimension-repository_parent_nwo" content="rdpeng/RepData_PeerAssessment1" /><meta name="octolytics-dimension-repository_network_root_id" content="16709733" /><meta name="octolytics-dimension-repository_network_root_nwo" content="rdpeng/RepData_PeerAssessment1" /><meta name="octolytics-dimension-repository_explore_github_marketplace_ci_cta_shown" content="false" />


    <link rel="canonical" href="https://github.com/Natasha-R/Reproducible-Research-Course-Project-1/blob/master/PA1_template.md" data-pjax-transient>


  <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">

  <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">

  <link rel="mask-icon" href="https://github.githubassets.com/pinned-octocat.svg" color="#000000">
  <link rel="icon" type="image/x-icon" class="js-site-favicon" href="https://github.githubassets.com/favicon.ico">

<meta name="theme-color" content="#1e2327">


  <link rel="manifest" href="/manifest.json" crossOrigin="use-credentials">

  </head>

  <body class="logged-in env-production page-responsive page-blob">
    

  <div class="position-relative js-header-wrapper ">
    <a href="#start-of-content" tabindex="1" class="p-3 bg-blue text-white show-on-focus js-skip-to-content">Skip to content</a>
    <span class="Progress progress-pjax-loader position-fixed width-full js-pjax-loader-bar">
      <span class="progress-pjax-loader-bar top-0 left-0" style="width: 0%;"></span>
    </span>

    
    



          <header class="Header js-details-container Details flex-wrap flex-lg-nowrap p-responsive" role="banner">

    <div class="Header-item d-none d-lg-flex">
      <a class="Header-link" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <svg class="octicon octicon-mark-github v-align-middle" height="32" viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"/></svg>
</a>

    </div>

    <div class="Header-item d-lg-none">
      <button class="Header-link btn-link js-details-target" type="button" aria-label="Toggle navigation" aria-expanded="false">
        <svg height="24" class="octicon octicon-three-bars" viewBox="0 0 12 16" version="1.1" width="18" aria-hidden="true"><path fill-rule="evenodd" d="M11.41 9H.59C0 9 0 8.59 0 8c0-.59 0-1 .59-1H11.4c.59 0 .59.41.59 1 0 .59 0 1-.59 1h.01zm0-4H.59C0 5 0 4.59 0 4c0-.59 0-1 .59-1H11.4c.59 0 .59.41.59 1 0 .59 0 1-.59 1h.01zM.59 11H11.4c.59 0 .59.41.59 1 0 .59 0 1-.59 1H.59C0 13 0 12.59 0 12c0-.59 0-1 .59-1z"/></svg>
      </button>
    </div>

    <div class="Header-item Header-item--full flex-column flex-lg-row width-full flex-order-2 flex-lg-order-none mr-0 mr-lg-3 mt-3 mt-lg-0 Details-content--hidden">
        <div class="header-search flex-self-stretch flex-lg-self-auto mr-0 mr-lg-3 mb-3 mb-lg-0 scoped-search site-scoped-search js-site-search position-relative js-jump-to"
  role="combobox"
  aria-owns="jump-to-results"
  aria-label="Search or jump to"
  aria-haspopup="listbox"
  aria-expanded="false"
>
  <div class="position-relative">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-site-search-form" role="search" aria-label="Site" data-scope-type="Repository" data-scope-id="42651708" data-scoped-search-url="/Natasha-R/Reproducible-Research-Course-Project-1/search" data-unscoped-search-url="/search" action="/Natasha-R/Reproducible-Research-Course-Project-1/search" accept-charset="UTF-8" method="get">
      <label class="form-control input-sm header-search-wrapper p-0 header-search-wrapper-jump-to position-relative d-flex flex-justify-between flex-items-center js-chromeless-input-container">
        <input type="text"
          class="form-control input-sm header-search-input jump-to-field js-jump-to-field js-site-search-focus js-site-search-field is-clearable"
          data-hotkey="s,/"
          name="q"
          value=""
          placeholder="Search or jump to…"
          data-unscoped-placeholder="Search or jump to…"
          data-scoped-placeholder="Search or jump to…"
          autocapitalize="off"
          aria-autocomplete="list"
          aria-controls="jump-to-results"
          aria-label="Search or jump to…"
          data-jump-to-suggestions-path="/_graphql/GetSuggestedNavigationDestinations"
          spellcheck="false"
          autocomplete="off"
          >
          <input type="hidden" value="X0XXoEHL8Rh33d0DGx7U1+Pn4h8vT44PGqsZCGIE3KKO+sIQBLpZgDA0vp0orXGKm7lX27ncOchUTaV2b2/13g==" data-csrf="true" class="js-data-jump-to-suggestions-path-csrf" />
          <input type="hidden" class="js-site-search-type-field" name="type" >
            <img src="https://github.githubassets.com/images/search-key-slash.svg" alt="" class="mr-2 header-search-key-slash">

            <div class="Box position-absolute overflow-hidden d-none jump-to-suggestions js-jump-to-suggestions-container">
              
<ul class="d-none js-jump-to-suggestions-template-container">
  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-suggestion" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 00-1 1v14a1 1 0 001 1h13a1 1 0 001-1V1a1 1 0 00-1-1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0013 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 000-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>

</ul>

<ul class="d-none js-jump-to-no-results-template-container">
  <li class="d-flex flex-justify-center flex-items-center f5 d-none js-jump-to-suggestion p-2">
    <span class="text-gray">No suggested jump to results</span>
  </li>
</ul>

<ul id="jump-to-results" role="listbox" class="p-0 m-0 js-navigation-container jump-to-suggestions-results-container js-jump-to-suggestions-results-container">
  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-scoped-search d-none" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 00-1 1v14a1 1 0 001 1h13a1 1 0 001-1V1a1 1 0 00-1-1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0013 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 000-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>

  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-global-search d-none" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 00-1 1v14a1 1 0 001 1h13a1 1 0 001-1V1a1 1 0 00-1-1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0013 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 000-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>


    <li class="d-flex flex-justify-center flex-items-center p-0 f5 js-jump-to-suggestion">
      <img src="https://github.githubassets.com/images/spinners/octocat-spinner-128.gif" alt="Octocat Spinner Icon" class="m-2" width="28">
    </li>
</ul>

            </div>
      </label>
</form>  </div>
</div>


        <nav class="d-flex flex-column flex-lg-row flex-self-stretch flex-lg-self-auto" aria-label="Global">
    <a class="Header-link d-block d-lg-none py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" data-ga-click="Header, click, Nav menu - item:dashboard:user" aria-label="Dashboard" href="/dashboard">
      Dashboard
</a>

  <a class="js-selected-navigation-item Header-link  mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" data-hotkey="g p" data-ga-click="Header, click, Nav menu - item:pulls context:user" aria-label="Pull requests you created" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls" href="/pulls">
    Pull requests
</a>
  <a class="js-selected-navigation-item Header-link  mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" data-hotkey="g i" data-ga-click="Header, click, Nav menu - item:issues context:user" aria-label="Issues you created" data-selected-links="/issues /issues/assigned /issues/mentioned /issues" href="/issues">
    Issues
</a>
    <div class="mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15">
      <a class="js-selected-navigation-item Header-link" data-ga-click="Header, click, Nav menu - item:marketplace context:user" data-octo-click="marketplace_click" data-octo-dimensions="location:nav_bar" data-selected-links=" /marketplace" href="/marketplace">
        Marketplace
</a>      

    </div>

  <a class="js-selected-navigation-item Header-link  mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" data-ga-click="Header, click, Nav menu - item:explore" data-selected-links="/explore /trending /trending/developers /integrations /integrations/feature/code /integrations/feature/collaborate /integrations/feature/ship showcases showcases_search showcases_landing /explore" href="/explore">
    Explore
</a>


    <a class="Header-link d-block d-lg-none mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" href="https://github.com/akshitkashyap">
      <img class="avatar" height="20" width="20" alt="@akshitkashyap" src="https://avatars2.githubusercontent.com/u/60666183?s=60&amp;v=4" />
      akshitkashyap
</a>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form action="/logout" accept-charset="UTF-8" method="post"><input type="hidden" name="authenticity_token" value="6A91vVT4wyno0sPnZ4C9b7LRe9d/q61M79hBYEm0us0D6YGJ2zFHKotIjUgJ38sue1Uh7p36enG/wLFItpgcWw==" />
      <button type="submit" class="Header-link mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15 d-lg-none btn-link d-block width-full text-left" data-ga-click="Header, sign out, icon:logout" style="padding-left: 2px;">
        <svg class="octicon octicon-sign-out v-align-middle" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 9V7H8V5h4V3l4 3-4 3zm-2 3H6V3L2 1h8v3h1V1c0-.55-.45-1-1-1H1C.45 0 0 .45 0 1v11.38c0 .39.22.73.55.91L6 16.01V13h4c.55 0 1-.45 1-1V8h-1v4z"/></svg>
        Sign out
      </button>
</form></nav>

    </div>

    <div class="Header-item Header-item--full flex-justify-center d-lg-none position-relative">
      <div class="css-truncate css-truncate-target width-fit position-absolute left-0 right-0 text-center">
              <svg class="octicon octicon-repo-forked" viewBox="0 0 10 16" version="1.1" width="10" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 00-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 002 1a1.993 1.993 0 00-1 3.72V6.5l3 3v1.78A1.993 1.993 0 005 15a1.993 1.993 0 001-3.72V9.5l3-3V4.72A1.993 1.993 0 008 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
    <a class="Header-link" href="/Natasha-R">Natasha-R</a>
    /
    <a class="Header-link" href="/Natasha-R/Reproducible-Research-Course-Project-1">Reproducible-Research-Course-Project-1</a>

</div>
    </div>

    <div class="Header-item mr-0 mr-lg-3 flex-order-1 flex-lg-order-none">
      

    <a aria-label="You have no unread notifications" class="Header-link notification-indicator position-relative tooltipped tooltipped-sw js-socket-channel js-notification-indicator" data-hotkey="g n" data-ga-click="Header, go to notifications, icon:read" data-channel="notification-changed:60666183" href="/notifications/beta">
        <span class="js-indicator-modifier mail-status "></span>
        <svg class="octicon octicon-bell" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 12v1H0v-1l.73-.58c.77-.77.81-2.55 1.19-4.42C2.69 3.23 6 2 6 2c0-.55.45-1 1-1s1 .45 1 1c0 0 3.39 1.23 4.16 5 .38 1.88.42 3.66 1.19 4.42l.66.58H14zm-7 4c1.11 0 2-.89 2-2H5c0 1.11.89 2 2 2z"/></svg>
</a>
    </div>


    <div class="Header-item position-relative d-none d-lg-flex">
      <details class="details-overlay details-reset">
  <summary class="Header-link"
      aria-label="Create new…"
      data-ga-click="Header, create new, icon:add">
    <svg class="octicon octicon-plus" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 9H7v5H5V9H0V7h5V2h2v5h5v2z"/></svg> <span class="dropdown-caret"></span>
  </summary>
  <details-menu class="dropdown-menu dropdown-menu-sw">
    
<a role="menuitem" class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>

  <a role="menuitem" class="dropdown-item" href="/new/import" data-ga-click="Header, import a repository">
    Import repository
  </a>

<a role="menuitem" class="dropdown-item" href="https://gist.github.com/" data-ga-click="Header, create new gist">
  New gist
</a>

  <a role="menuitem" class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>



  <a role="menuitem" class="dropdown-item" href="/new/project" data-ga-click="Header, create new project">
    New project
  </a>

  </details-menu>
</details>

    </div>

    <div class="Header-item position-relative mr-0 d-none d-lg-flex">
      
  <details class="details-overlay details-reset js-feature-preview-indicator-container" data-feature-preview-indicator-src="/users/akshitkashyap/feature_preview/indicator_check.json">

  <summary class="Header-link"
    aria-label="View profile and more"
    data-ga-click="Header, show menu, icon:avatar">
    <img class="avatar " alt="@akshitkashyap" width="20" height="20" src="https://avatars2.githubusercontent.com/u/60666183?s=60&amp;v=4">


      <span class="feature-preview-indicator js-feature-preview-indicator" hidden></span>
    <span class="dropdown-caret"></span>
  </summary>
  <details-menu class="dropdown-menu dropdown-menu-sw mt-2" style="width: 180px">
    <div class="header-nav-current-user css-truncate"><a role="menuitem" class="no-underline user-profile-link px-3 pt-2 pb-2 mb-n2 mt-n1 d-block" href="/akshitkashyap" data-ga-click="Header, go to profile, text:Signed in as">Signed in as <strong class="css-truncate-target">akshitkashyap</strong></a></div>
    <div role="none" class="dropdown-divider"></div>

      <div class="pl-3 pr-3 f6 user-status-container js-user-status-context pb-1" data-url="/users/status?compact=1&amp;link_mentions=0&amp;truncate=1">
        
<div class="js-user-status-container
    user-status-compact rounded-1 px-2 py-1 mt-2
    border
  " data-team-hovercards-enabled>
  <details class="js-user-status-details details-reset details-overlay details-overlay-dark">
    <summary class="btn-link btn-block link-gray no-underline js-toggle-user-status-edit toggle-user-status-edit "
      role="menuitem" data-hydro-click="{&quot;event_type&quot;:&quot;user_profile.click&quot;,&quot;payload&quot;:{&quot;profile_user_id&quot;:12715753,&quot;target&quot;:&quot;EDIT_USER_STATUS&quot;,&quot;user_id&quot;:60666183,&quot;originating_url&quot;:&quot;https://github.com/Natasha-R/Reproducible-Research-Course-Project-1/blob/master/PA1_template.md&quot;}}" data-hydro-click-hmac="9aca094344f49b81fb80e4ad6ea0412fedf18bdf8ca99696a33535e6e03af3e6">
      <div class="d-flex">
        <div class="f6 lh-condensed user-status-header
          d-inline-block v-align-middle
            user-status-emoji-only-header circle
            pr-2
"
            style="max-width: 29px"
          >
          <div class="user-status-emoji-container flex-shrink-0 mr-1 mt-1 lh-condensed-ultra v-align-bottom" style="">
            <svg class="octicon octicon-smiley" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8s3.58 8 8 8 8-3.58 8-8-3.58-8-8-8zm4.81 12.81a6.72 6.72 0 01-2.17 1.45c-.83.36-1.72.53-2.64.53-.92 0-1.81-.17-2.64-.53-.81-.34-1.55-.83-2.17-1.45a6.773 6.773 0 01-1.45-2.17A6.59 6.59 0 011.21 8c0-.92.17-1.81.53-2.64.34-.81.83-1.55 1.45-2.17.62-.62 1.36-1.11 2.17-1.45A6.59 6.59 0 018 1.21c.92 0 1.81.17 2.64.53.81.34 1.55.83 2.17 1.45.62.62 1.11 1.36 1.45 2.17.36.83.53 1.72.53 2.64 0 .92-.17 1.81-.53 2.64-.34.81-.83 1.55-1.45 2.17zM4 6.8v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2H5.2C4.53 8 4 7.47 4 6.8zm5 0v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2h-.59C9.53 8 9 7.47 9 6.8zm4 3.2c-.72 1.88-2.91 3-5 3s-4.28-1.13-5-3c-.14-.39.23-1 .66-1h8.59c.41 0 .89.61.75 1z"/></svg>
          </div>
        </div>
        <div class="
          d-inline-block v-align-middle
          
          
           css-truncate css-truncate-target 
           user-status-message-wrapper f6"
           style="line-height: 20px;" >
          <div class="d-inline-block text-gray-dark v-align-text-top text-left">
              <span class="text-gray ml-2">Set status</span>
          </div>
        </div>
      </div>
    </summary>
    <details-dialog class="details-dialog rounded-1 anim-fade-in fast Box Box--overlay" role="dialog" tabindex="-1">
      <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="position-relative flex-auto js-user-status-form" action="/users/status?compact=1&amp;link_mentions=0&amp;truncate=1" accept-charset="UTF-8" method="post"><input type="hidden" name="_method" value="put" /><input type="hidden" name="authenticity_token" value="hBmF3E/SHd9Zupw1RZP0AHfqR5s3v2WUwtMp+b+VnF9rR3xgILzVii59UzozEGhq06u7CuoOW9+FyvB86Dl4Dg==" />
        <div class="Box-header bg-gray border-bottom p-3">
          <button class="Box-btn-octicon js-toggle-user-status-edit btn-octicon float-right" type="reset" aria-label="Close dialog" data-close-dialog>
            <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
          </button>
          <h3 class="Box-title f5 text-bold text-gray-dark">Edit status</h3>
        </div>
        <input type="hidden" name="emoji" class="js-user-status-emoji-field" value="">
        <input type="hidden" name="organization_id" class="js-user-status-org-id-field" value="">
        <div class="px-3 py-2 text-gray-dark">
          <div class="js-characters-remaining-container position-relative mt-2">
            <div class="input-group d-table form-group my-0 js-user-status-form-group">
              <span class="input-group-button d-table-cell v-align-middle" style="width: 1%">
                <button type="button" aria-label="Choose an emoji" class="btn-outline btn js-toggle-user-status-emoji-picker btn-open-emoji-picker p-0">
                  <span class="js-user-status-original-emoji" hidden></span>
                  <span class="js-user-status-custom-emoji"></span>
                  <span class="js-user-status-no-emoji-icon" >
                    <svg class="octicon octicon-smiley" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8s3.58 8 8 8 8-3.58 8-8-3.58-8-8-8zm4.81 12.81a6.72 6.72 0 01-2.17 1.45c-.83.36-1.72.53-2.64.53-.92 0-1.81-.17-2.64-.53-.81-.34-1.55-.83-2.17-1.45a6.773 6.773 0 01-1.45-2.17A6.59 6.59 0 011.21 8c0-.92.17-1.81.53-2.64.34-.81.83-1.55 1.45-2.17.62-.62 1.36-1.11 2.17-1.45A6.59 6.59 0 018 1.21c.92 0 1.81.17 2.64.53.81.34 1.55.83 2.17 1.45.62.62 1.11 1.36 1.45 2.17.36.83.53 1.72.53 2.64 0 .92-.17 1.81-.53 2.64-.34.81-.83 1.55-1.45 2.17zM4 6.8v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2H5.2C4.53 8 4 7.47 4 6.8zm5 0v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2h-.59C9.53 8 9 7.47 9 6.8zm4 3.2c-.72 1.88-2.91 3-5 3s-4.28-1.13-5-3c-.14-.39.23-1 .66-1h8.59c.41 0 .89.61.75 1z"/></svg>
                  </span>
                </button>
              </span>
              <text-expander keys=": @" data-mention-url="/autocomplete/user-suggestions" data-emoji-url="/autocomplete/emoji">
                <input
                  type="text"
                  autocomplete="off"
                  data-no-org-url="/autocomplete/user-suggestions"
                  data-org-url="/suggestions?mention_suggester=1"
                  data-maxlength="80"
                  class="d-table-cell width-full form-control js-user-status-message-field js-characters-remaining-field"
                  placeholder="What's happening?"
                  name="message"
                  value=""
                  aria-label="What is your current status?">
              </text-expander>
              <div class="error">Could not update your status, please try again.</div>
            </div>
            <div style="margin-left: 53px" class="my-1 text-small label-characters-remaining js-characters-remaining" data-suffix="remaining" hidden>
              80 remaining
            </div>
          </div>
          <include-fragment class="js-user-status-emoji-picker" data-url="/users/status/emoji"></include-fragment>
          <div class="overflow-auto ml-n3 mr-n3 px-3 border-bottom" style="max-height: 33vh">
            <div class="user-status-suggestions js-user-status-suggestions collapsed overflow-hidden">
              <h4 class="f6 text-normal my-3">Suggestions:</h4>
              <div class="mx-3 mt-2 clearfix">
                  <div class="float-left col-6">
                      <button type="button" value=":palm_tree:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="palm_tree" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f334.png">🌴</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          On vacation
                        </div>
                      </button>
                      <button type="button" value=":face_with_thermometer:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="face_with_thermometer" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f912.png">🤒</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          Out sick
                        </div>
                      </button>
                  </div>
                  <div class="float-left col-6">
                      <button type="button" value=":house:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="house" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f3e0.png">🏠</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          Working from home
                        </div>
                      </button>
                      <button type="button" value=":dart:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="dart" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f3af.png">🎯</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          Focusing
                        </div>
                      </button>
                  </div>
              </div>
            </div>
            <div class="user-status-limited-availability-container">
              <div class="form-checkbox my-0">
                <input type="checkbox" name="limited_availability" value="1" class="js-user-status-limited-availability-checkbox" data-default-message="I may be slow to respond." aria-describedby="limited-availability-help-text-truncate-true-compact-true" id="limited-availability-truncate-true-compact-true">
                <label class="d-block f5 text-gray-dark mb-1" for="limited-availability-truncate-true-compact-true">
                  Busy
                </label>
                <p class="note" id="limited-availability-help-text-truncate-true-compact-true">
                  When others mention you, assign you, or request your review,
                  GitHub will let them know that you have limited availability.
                </p>
              </div>
            </div>
          </div>
          <div class="d-inline-block f5 mr-2 pt-3 pb-2" >
  <div class="d-inline-block mr-1">
    Clear status
  </div>

  <details class="js-user-status-expire-drop-down f6 dropdown details-reset details-overlay d-inline-block mr-2">
    <summary class="f5 btn-link link-gray-dark border px-2 py-1 rounded-1" aria-haspopup="true">
      <div class="js-user-status-expiration-interval-selected d-inline-block v-align-baseline">
        Never
      </div>
      <div class="dropdown-caret"></div>
    </summary>

    <ul class="dropdown-menu dropdown-menu-se pl-0 overflow-auto" style="width: 220px; max-height: 15.5em">
      <li>
        <button type="button" class="btn-link dropdown-item js-user-status-expire-button ws-normal" title="Never">
          <span class="d-inline-block text-bold mb-1">Never</span>
          <div class="f6 lh-condensed">Keep this status until you clear your status or edit your status.</div>
        </button>
      </li>
      <li class="dropdown-divider" role="none"></li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="in 30 minutes" value="2020-03-12T00:03:51+05:30">
            in 30 minutes
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="in 1 hour" value="2020-03-12T00:33:51+05:30">
            in 1 hour
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="in 4 hours" value="2020-03-12T03:33:51+05:30">
            in 4 hours
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="today" value="2020-03-11T23:59:59+05:30">
            today
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="this week" value="2020-03-15T23:59:59+05:30">
            this week
          </button>
        </li>
    </ul>
  </details>
  <input class="js-user-status-expiration-date-input" type="hidden" name="expires_at" value="">
</div>

          <include-fragment class="js-user-status-org-picker" data-url="/users/status/organizations"></include-fragment>
        </div>
        <div class="d-flex flex-items-center flex-justify-between p-3 border-top">
          <button type="submit" disabled class="width-full btn btn-primary mr-2 js-user-status-submit">
            Set status
          </button>
          <button type="button" disabled class="width-full js-clear-user-status-button btn ml-2 ">
            Clear status
          </button>
        </div>
</form>    </details-dialog>
  </details>
</div>

      </div>
      <div role="none" class="dropdown-divider"></div>


    <a role="menuitem" class="dropdown-item" href="/akshitkashyap" data-ga-click="Header, go to profile, text:your profile">Your profile</a>

    <a role="menuitem" class="dropdown-item" href="/akshitkashyap?tab=repositories" data-ga-click="Header, go to repositories, text:your repositories">Your repositories</a>

    <a role="menuitem" class="dropdown-item" href="/akshitkashyap?tab=projects" data-ga-click="Header, go to projects, text:your projects">Your projects</a>

    <a role="menuitem" class="dropdown-item" href="/akshitkashyap?tab=stars" data-ga-click="Header, go to starred repos, text:your stars">Your stars</a>
      <a role="menuitem" class="dropdown-item" href="https://gist.github.com/mine" data-ga-click="Header, your gists, text:your gists">Your gists</a>





    <div role="none" class="dropdown-divider"></div>
      
<div id="feature-enrollment-toggle" class="hide-sm hide-md feature-preview-details position-relative">
  <button
    type="button"
    class="dropdown-item btn-link"
    role="menuitem"
    data-feature-preview-trigger-url="/users/akshitkashyap/feature_previews"
    data-feature-preview-close-details="{&quot;event_type&quot;:&quot;feature_preview.clicks.close_modal&quot;,&quot;payload&quot;:{&quot;originating_url&quot;:&quot;https://github.com/Natasha-R/Reproducible-Research-Course-Project-1/blob/master/PA1_template.md&quot;,&quot;user_id&quot;:60666183}}"
    data-feature-preview-close-hmac="1f069874440c62a67435841ef8ba8b11d2c52449fd66ec31cc63c207dd15699f"
    data-hydro-click="{&quot;event_type&quot;:&quot;feature_preview.clicks.open_modal&quot;,&quot;payload&quot;:{&quot;link_location&quot;:&quot;user_dropdown&quot;,&quot;originating_url&quot;:&quot;https://github.com/Natasha-R/Reproducible-Research-Course-Project-1/blob/master/PA1_template.md&quot;,&quot;user_id&quot;:60666183}}"
    data-hydro-click-hmac="7a951ae2991c144d0e24b935ca5db4746c6a8aeb82da16bd64bcb2648b0bd19c"
  >
    Feature preview
  </button>
    <span class="feature-preview-indicator js-feature-preview-indicator" hidden></span>
</div>

    <a role="menuitem" class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">Help</a>
    <a role="menuitem" class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">Settings</a>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="logout-form" action="/logout" accept-charset="UTF-8" method="post"><input type="hidden" name="authenticity_token" value="/wtyUHdIyR5qOq3z6zL9d72Uyh105A8XZ+FYqpEuD8cU7YZk+IFNHQmg41yFbYs2dBCQJJa12Co3+aiCbgKpUQ==" />
      
      <button type="submit" class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout" role="menuitem">
        Sign out
      </button>
      <input type="text" name="required_field_32dd" hidden="hidden" class="form-control" /><input type="hidden" name="timestamp" value="1583949831400" class="form-control" /><input type="hidden" name="timestamp_secret" value="986967d8b9a29041284842cf493a1f51f7211c71225a5f13583cbf63ea0ba46d" class="form-control" />
</form>  </details-menu>
</details>

    </div>

  </header>

      

  </div>

  <div id="start-of-content" class="show-on-focus"></div>


    <div id="js-flash-container">

</div>


      

  <include-fragment class="js-notification-shelf-include-fragment" data-base-src="https://github.com/notifications/beta/shelf"></include-fragment>




  <div class="application-main " data-commit-hovercards-enabled>
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode" class="">
    <main  >
      

  











  <div class="pagehead repohead hx_repohead readability-menu bg-gray-light pb-0 pt-0 pt-lg-3">

    <div class="d-flex container-lg mb-4 p-responsive d-none d-lg-flex">

      <div class="flex-auto min-width-0 width-fit mr-3">
        <h1 class="public  d-flex flex-wrap flex-items-center break-word float-none ">
    <svg class="octicon octicon-repo-forked" viewBox="0 0 10 16" version="1.1" width="10" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 00-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 002 1a1.993 1.993 0 00-1 3.72V6.5l3 3v1.78A1.993 1.993 0 005 15a1.993 1.993 0 001-3.72V9.5l3-3V4.72A1.993 1.993 0 008 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
  <span class="author ml-1 flex-self-stretch" itemprop="author">
    <a class="url fn" rel="author" data-hovercard-type="user" data-hovercard-url="/users/Natasha-R/hovercard" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/Natasha-R">Natasha-R</a>
  </span>
  <span class="path-divider flex-self-stretch">/</span>
  <strong itemprop="name" class="mr-2 flex-self-stretch">
    <a data-pjax="#js-repo-pjax-container" href="/Natasha-R/Reproducible-Research-Course-Project-1">Reproducible-Research-Course-Project-1</a>
  </strong>
  
</h1>

  <span class="fork-flag mt-1" data-repository-hovercards-enabled>
    <span class="text">forked from <a data-hovercard-type="repository" data-hovercard-url="/rdpeng/RepData_PeerAssessment1/hovercard" href="/rdpeng/RepData_PeerAssessment1">rdpeng/RepData_PeerAssessment1</a></span>
  </span>

      </div>

      <ul class="pagehead-actions flex-shrink-0 " >




  <li>
    
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form data-remote="true" class="clearfix js-social-form js-social-container" action="/notifications/subscribe" accept-charset="UTF-8" method="post"><input type="hidden" name="authenticity_token" value="EQo9gIFOHjb2fTMpFXj1+PQKYQM2hnQLusNe62ZSCuczqb/Ar00Hj2mqlbnz7S1ciWvjCSqRsaxsRGkWMsXqMg==" />      <input type="hidden" name="repository_id" value="42651708">

      <details class="details-reset details-overlay select-menu float-left">
        <summary class="select-menu-button float-left btn btn-sm btn-with-count" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;WATCH_BUTTON&quot;,&quot;repository_id&quot;:42651708,&quot;originating_url&quot;:&quot;https://github.com/Natasha-R/Reproducible-Research-Course-Project-1/blob/master/PA1_template.md&quot;,&quot;user_id&quot;:60666183}}" data-hydro-click-hmac="fd1f713c9eee96d1a9b8068fb1e22576a2a37f6c4d8811657615c7f8caf641ec" data-ga-click="Repository, click Watch settings, action:blob#show">          <span data-menu-button>
              <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
              Watch
          </span>
</summary>        <details-menu
          class="select-menu-modal position-absolute mt-5"
          style="z-index: 99;">
          <div class="select-menu-header">
            <span class="select-menu-title">Notifications</span>
          </div>
          <div class="select-menu-list">
            <button type="submit" name="do" value="included" class="select-menu-item width-full" aria-checked="true" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Not watching</span>
                <span class="description">Be notified only when participating or @mentioned.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                  Watch
                </span>
              </div>
            </button>

            <button type="submit" name="do" value="release_only" class="select-menu-item width-full" aria-checked="false" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Releases only</span>
                <span class="description">Be notified of new releases, and when participating or @mentioned.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                  Unwatch releases
                </span>
              </div>
            </button>

            <button type="submit" name="do" value="subscribed" class="select-menu-item width-full" aria-checked="false" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Watching</span>
                <span class="description">Be notified of all conversations.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                  Unwatch
                </span>
              </div>
            </button>

            <button type="submit" name="do" value="ignore" class="select-menu-item width-full" aria-checked="false" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Ignoring</span>
                <span class="description">Never be notified.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-mute v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 2.81v10.38c0 .67-.81 1-1.28.53L3 10H1c-.55 0-1-.45-1-1V7c0-.55.45-1 1-1h2l3.72-3.72C7.19 1.81 8 2.14 8 2.81zm7.53 3.22l-1.06-1.06-1.97 1.97-1.97-1.97-1.06 1.06L11.44 8 9.47 9.97l1.06 1.06 1.97-1.97 1.97 1.97 1.06-1.06L13.56 8l1.97-1.97z"/></svg>
                  Stop ignoring
                </span>
              </div>
            </button>
          </div>
        </details-menu>
      </details>
        <a class="social-count js-social-count"
          href="/Natasha-R/Reproducible-Research-Course-Project-1/watchers"
          aria-label="1 user is watching this repository">
          1
        </a>
</form>
  </li>

  <li>
      <div class="js-toggler-container js-social-container starring-container ">
    <form class="starred js-social-form" action="/Natasha-R/Reproducible-Research-Course-Project-1/unstar" accept-charset="UTF-8" method="post"><input type="hidden" name="authenticity_token" value="kRgHqftWA7zZDmKFERCwtV3cXF8ufCCgDWWqocBHMlNcmW/2HeHR2qb+9rJrjR4MmlkjLF/rkY1m8dpORgR6ng==" />
      <input type="hidden" name="context" value="repository"></input>
      <button type="submit" class="btn btn-sm btn-with-count js-toggler-target" aria-label="Unstar this repository" title="Unstar Natasha-R/Reproducible-Research-Course-Project-1" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;UNSTAR_BUTTON&quot;,&quot;repository_id&quot;:42651708,&quot;originating_url&quot;:&quot;https://github.com/Natasha-R/Reproducible-Research-Course-Project-1/blob/master/PA1_template.md&quot;,&quot;user_id&quot;:60666183}}" data-hydro-click-hmac="ae60ee2edeb2499864c6c236b673a1dbbbe4582795fd0ac0b976d18810174ebc" data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">        <svg height="16" class="octicon octicon-star v-align-text-bottom" vertical_align="text_bottom" viewBox="0 0 14 16" version="1.1" width="14" aria-hidden="true"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74L14 6z"/></svg>

        Unstar
</button>        <a class="social-count js-social-count" href="/Natasha-R/Reproducible-Research-Course-Project-1/stargazers"
           aria-label="0 users starred this repository">
           0
        </a>
</form>
    <form class="unstarred js-social-form" action="/Natasha-R/Reproducible-Research-Course-Project-1/star" accept-charset="UTF-8" method="post"><input type="hidden" name="authenticity_token" value="j/E04qoxF2LolYuOuz5IOiZ11feaUjYyHngR8s24XWCTo+P4WzhHuGeyQ1H2AKBff8WbUirbJrUFca24N9bnRQ==" />
      <input type="hidden" name="context" value="repository"></input>
      <button type="submit" class="btn btn-sm btn-with-count js-toggler-target" aria-label="Unstar this repository" title="Star Natasha-R/Reproducible-Research-Course-Project-1" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;STAR_BUTTON&quot;,&quot;repository_id&quot;:42651708,&quot;originating_url&quot;:&quot;https://github.com/Natasha-R/Reproducible-Research-Course-Project-1/blob/master/PA1_template.md&quot;,&quot;user_id&quot;:60666183}}" data-hydro-click-hmac="31a2bb4b95568bbd52e75fe089dbdc3cd3d90df2f786ea473a578b8568df2aa6" data-ga-click="Repository, click star button, action:blob#show; text:Star">        <svg height="16" class="octicon octicon-star v-align-text-bottom" vertical_align="text_bottom" viewBox="0 0 14 16" version="1.1" width="14" aria-hidden="true"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74L14 6z"/></svg>

        Star
</button>        <a class="social-count js-social-count" href="/Natasha-R/Reproducible-Research-Course-Project-1/stargazers"
           aria-label="0 users starred this repository">
          0
        </a>
</form>  </div>

  </li>

  <li>
          <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="btn-with-count" action="/Natasha-R/Reproducible-Research-Course-Project-1/fork" accept-charset="UTF-8" method="post"><input type="hidden" name="authenticity_token" value="uWIwrg68YKaDUSVjJo7AYN1oYbBB0ZQAytUiwSjkzo3Xy5khKgDf2bWKT/FXLg/BGy7+/o1GUcQo0BS5snNv6A==" />
            <button class="btn btn-sm btn-with-count" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;FORK_BUTTON&quot;,&quot;repository_id&quot;:42651708,&quot;originating_url&quot;:&quot;https://github.com/Natasha-R/Reproducible-Research-Course-Project-1/blob/master/PA1_template.md&quot;,&quot;user_id&quot;:60666183}}" data-hydro-click-hmac="9374a73939ab69f3503d0914bd3560ee187f0db2dca14a6e6ef8fd3005f8c079" data-ga-click="Repository, show fork modal, action:blob#show; text:Fork" type="submit" title="Fork your own copy of Natasha-R/Reproducible-Research-Course-Project-1 to your account" aria-label="Fork your own copy of Natasha-R/Reproducible-Research-Course-Project-1 to your account">              <svg class="octicon octicon-repo-forked v-align-text-bottom" viewBox="0 0 10 16" version="1.1" width="10" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 00-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 002 1a1.993 1.993 0 00-1 3.72V6.5l3 3v1.78A1.993 1.993 0 005 15a1.993 1.993 0 001-3.72V9.5l3-3V4.72A1.993 1.993 0 008 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
              Fork
</button></form>
    <a href="/Natasha-R/Reproducible-Research-Course-Project-1/network/members" class="social-count"
       aria-label="32472 users forked this repository">
      32.5k
    </a>
  </li>
</ul>

    </div>
      
<nav class="hx_reponav reponav js-repo-nav js-sidenav-container-pjax clearfix container-lg p-responsive d-none d-lg-block"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
    aria-label="Repository"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a class="js-selected-navigation-item selected reponav-item" itemprop="url" data-hotkey="g c" aria-current="page" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /Natasha-R/Reproducible-Research-Course-Project-1" href="/Natasha-R/Reproducible-Research-Course-Project-1">
      <div class="d-inline"><svg class="octicon octicon-code" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"/></svg></div>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>


  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a data-hotkey="g p" data-skip-pjax="true" itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_pulls checks /Natasha-R/Reproducible-Research-Course-Project-1/pulls" href="/Natasha-R/Reproducible-Research-Course-Project-1/pulls">
      <div class="d-inline"><svg class="octicon octicon-git-pull-request" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0010 15a1.993 1.993 0 001-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 00-1 3.72v6.56A1.993 1.993 0 002 15a1.993 1.993 0 001-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg></div>
      <span itemprop="name">Pull requests</span>
      <span class="Counter">0</span>
      <meta itemprop="position" content="4">
</a>  </span>


    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement" class="position-relative float-left">
      <a data-hotkey="g w" data-skip-pjax="true" class="js-selected-navigation-item reponav-item" data-selected-links="repo_actions /Natasha-R/Reproducible-Research-Course-Project-1/actions" href="/Natasha-R/Reproducible-Research-Course-Project-1/actions">
        <div class="d-inline"><svg class="octicon octicon-play" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 8A7 7 0 110 8a7 7 0 0114 0zm-8.223 3.482l4.599-3.066a.5.5 0 000-.832L5.777 4.518A.5.5 0 005 4.934v6.132a.5.5 0 00.777.416z"/></svg></div>
        Actions
</a>
    </span>

    <a data-hotkey="g b" class="js-selected-navigation-item reponav-item" data-selected-links="repo_projects new_repo_project repo_project /Natasha-R/Reproducible-Research-Course-Project-1/projects" href="/Natasha-R/Reproducible-Research-Course-Project-1/projects">
      <div class="d-inline"><svg class="octicon octicon-project" viewBox="0 0 15 16" version="1.1" width="15" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 00-1 1v14a1 1 0 001 1h13a1 1 0 001-1V1a1 1 0 00-1-1z"/></svg></div>
      Projects
      <span class="Counter">0</span>
</a>
    <a class="js-selected-navigation-item reponav-item" data-hotkey="g w" data-selected-links="repo_wiki /Natasha-R/Reproducible-Research-Course-Project-1/wiki" href="/Natasha-R/Reproducible-Research-Course-Project-1/wiki">
      <div class="d-inline"><svg class="octicon octicon-book" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M3 5h4v1H3V5zm0 3h4V7H3v1zm0 2h4V9H3v1zm11-5h-4v1h4V5zm0 2h-4v1h4V7zm0 2h-4v1h4V9zm2-6v9c0 .55-.45 1-1 1H9.5l-1 1-1-1H2c-.55 0-1-.45-1-1V3c0-.55.45-1 1-1h5.5l1 1 1-1H15c.55 0 1 .45 1 1zm-8 .5L7.5 3H2v9h6V3.5zm7-.5H9.5l-.5.5V12h6V3z"/></svg></div>
      Wiki
</a>
    <a data-skip-pjax="true" class="js-selected-navigation-item reponav-item" data-selected-links="security alerts policy token_scanning code_scanning /Natasha-R/Reproducible-Research-Course-Project-1/security/advisories" href="/Natasha-R/Reproducible-Research-Course-Project-1/security/advisories">
      <div class="d-inline"><svg class="octicon octicon-shield" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 2l7-2 7 2v6.02C14 12.69 8.69 16 7 16c-1.69 0-7-3.31-7-7.98V2zm1 .75L7 1l6 1.75v5.268C13 12.104 8.449 15 7 15c-1.449 0-6-2.896-6-6.982V2.75zm1 .75L7 2v12c-1.207 0-5-2.482-5-5.985V3.5z"/></svg></div>
      Security
</a>
    <a class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors dependency_graph pulse people /Natasha-R/Reproducible-Research-Course-Project-1/pulse" href="/Natasha-R/Reproducible-Research-Course-Project-1/pulse">
      <div class="d-inline"><svg class="octicon octicon-graph" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"/></svg></div>
      Insights
</a>

</nav>

  <div class="reponav-wrapper reponav-small d-lg-none">
  <nav class="reponav js-reponav text-center no-wrap"
       itemscope
       itemtype="http://schema.org/BreadcrumbList">

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a class="js-selected-navigation-item selected reponav-item" itemprop="url" aria-current="page" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /Natasha-R/Reproducible-Research-Course-Project-1" href="/Natasha-R/Reproducible-Research-Course-Project-1">
        <span itemprop="name">Code</span>
        <meta itemprop="position" content="1">
</a>    </span>


    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_pulls checks /Natasha-R/Reproducible-Research-Course-Project-1/pulls" href="/Natasha-R/Reproducible-Research-Course-Project-1/pulls">
        <span itemprop="name">Pull requests</span>
        <span class="Counter">0</span>
        <meta itemprop="position" content="4">
</a>    </span>


      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_projects new_repo_project repo_project /Natasha-R/Reproducible-Research-Course-Project-1/projects" href="/Natasha-R/Reproducible-Research-Course-Project-1/projects">
          <span itemprop="name">Projects</span>
          <span class="Counter">0</span>
          <meta itemprop="position" content="5">
</a>      </span>

      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_actions /Natasha-R/Reproducible-Research-Course-Project-1/actions" href="/Natasha-R/Reproducible-Research-Course-Project-1/actions">
          <span itemprop="name">Actions</span>
          <meta itemprop="position" content="6">
</a>      </span>

      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_wiki /Natasha-R/Reproducible-Research-Course-Project-1/wiki" href="/Natasha-R/Reproducible-Research-Course-Project-1/wiki">
          <span itemprop="name">Wiki</span>
          <meta itemprop="position" content="7">
</a>      </span>

      <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="security alerts policy token_scanning code_scanning /Natasha-R/Reproducible-Research-Course-Project-1/security/advisories" href="/Natasha-R/Reproducible-Research-Course-Project-1/security/advisories">
        <span itemprop="name">Security</span>
        <meta itemprop="position" content="8">
</a>
      <a class="js-selected-navigation-item reponav-item" data-selected-links="pulse /Natasha-R/Reproducible-Research-Course-Project-1/pulse" href="/Natasha-R/Reproducible-Research-Course-Project-1/pulse">
        Pulse
</a>

  </nav>
</div>


  </div>

  

  <include-fragment class="js-notification-shelf-include-fragment" data-base-src="https://github.com/notifications/beta/shelf"></include-fragment>


<div class="container-lg clearfix new-discussion-timeline  p-responsive">
  <div class="repository-content ">

    
    


  


    <a class="d-none js-permalink-shortcut" data-hotkey="y" href="/Natasha-R/Reproducible-Research-Course-Project-1/blob/f11bc1b49a95abc49658650d99d3c5a7cae7a87a/PA1_template.md">Permalink</a>

    <!-- blob contrib key: blob_contributors:v22:433e7fc8300fdbcd45d1d9f6d5e6dadb -->
    

    <div class="d-flex flex-items-start flex-shrink-0 flex-column flex-md-row pb-3">
      <span class="d-flex flex-justify-between width-full width-md-auto">
        
<details class="details-reset details-overlay branch-select-menu " id="branch-select-menu">
  <summary class="btn btn-sm css-truncate"
           data-hotkey="w"
           title="Switch branches or tags">
    <i>Branch:</i>
    <span class="css-truncate-target" data-menu-button>master</span>
    <span class="dropdown-caret"></span>
  </summary>

  <details-menu class="SelectMenu SelectMenu--hasFilter" src="/Natasha-R/Reproducible-Research-Course-Project-1/refs/master/PA1_template.md?source_action=show&amp;source_controller=blob" preload>
    <div class="SelectMenu-modal">
      <include-fragment class="SelectMenu-loading" aria-label="Menu is loading">
        <svg class="octicon octicon-octoface anim-pulse" height="32" viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true"><path fill-rule="evenodd" d="M14.7 5.34c.13-.32.55-1.59-.13-3.31 0 0-1.05-.33-3.44 1.3-1-.28-2.07-.32-3.13-.32s-2.13.04-3.13.32c-2.39-1.64-3.44-1.3-3.44-1.3-.68 1.72-.26 2.99-.13 3.31C.49 6.21 0 7.33 0 8.69 0 13.84 3.33 15 7.98 15S16 13.84 16 8.69c0-1.36-.49-2.48-1.3-3.35zM8 14.02c-3.3 0-5.98-.15-5.98-3.35 0-.76.38-1.48 1.02-2.07 1.07-.98 2.9-.46 4.96-.46 2.07 0 3.88-.52 4.96.46.65.59 1.02 1.3 1.02 2.07 0 3.19-2.68 3.35-5.98 3.35zM5.49 9.01c-.66 0-1.2.8-1.2 1.78s.54 1.79 1.2 1.79c.66 0 1.2-.8 1.2-1.79s-.54-1.78-1.2-1.78zm5.02 0c-.66 0-1.2.79-1.2 1.78s.54 1.79 1.2 1.79c.66 0 1.2-.8 1.2-1.79s-.53-1.78-1.2-1.78z"/></svg>
      </include-fragment>
    </div>
  </details-menu>
</details>

        <div class="BtnGroup flex-shrink-0 d-md-none">
          <a href="/Natasha-R/Reproducible-Research-Course-Project-1/find/master"
                class="js-pjax-capture-input btn btn-sm BtnGroup-item"
                data-pjax
                data-hotkey="t">
            Find file
          </a>
          <clipboard-copy value="PA1_template.md" class="btn btn-sm BtnGroup-item">
            Copy path
          </clipboard-copy>
        </div>
      </span>
      <h2 id="blob-path" class="breadcrumb flex-auto min-width-0 text-normal flex-md-self-center ml-md-2 mr-md-3 my-2 my-md-0">
        <span class="js-repo-root text-bold"><span class="js-path-segment"><a data-pjax="true" href="/Natasha-R/Reproducible-Research-Course-Project-1"><span>Reproducible-Research-Course-Project-1</span></a></span></span><span class="separator">/</span><strong class="final-path">PA1_template.md</strong>
      </h2>

      <div class="BtnGroup flex-shrink-0 d-none d-md-inline-block">
        <a href="/Natasha-R/Reproducible-Research-Course-Project-1/find/master"
              class="js-pjax-capture-input btn btn-sm BtnGroup-item"
              data-pjax
              data-hotkey="t">
          Find file
        </a>
        <clipboard-copy value="PA1_template.md" class="btn btn-sm BtnGroup-item">
          Copy path
        </clipboard-copy>
      </div>
    </div>

    



    <include-fragment src="/Natasha-R/Reproducible-Research-Course-Project-1/contributors/master/PA1_template.md" class="Box Box--condensed commit-loader">
      <div class="Box-body bg-blue-light f6">
        Fetching contributors&hellip;
      </div>

      <div class="Box-body d-flex flex-items-center" >
        <img alt="" class="loader-loading mr-2" src="https://github.githubassets.com/images/spinners/octocat-spinner-32-EAF2F5.gif" width="16" height="16" />
        <span class="text-red h6 loader-error">Cannot retrieve contributors at this time</span>
      </div>
</include-fragment>





    <div class="Box mt-3 position-relative">
      
<div class="Box-header py-2 d-flex flex-column flex-shrink-0 flex-md-row flex-md-items-center">
  <div class="text-mono f6 flex-auto pr-3 flex-order-2 flex-md-order-1 mt-2 mt-md-0">

      387 lines (276 sloc)
      <span class="file-info-divider"></span>
    13.9 KB
  </div>

  <div class="d-flex py-1 py-md-0 flex-auto flex-order-1 flex-md-order-2 flex-sm-grow-0 flex-justify-between">

    <div class="BtnGroup">
      <a id="raw-url" class="btn btn-sm BtnGroup-item" href="/Natasha-R/Reproducible-Research-Course-Project-1/raw/master/PA1_template.md">Raw</a>
        <a class="btn btn-sm js-update-url-with-hash BtnGroup-item" data-hotkey="b" href="/Natasha-R/Reproducible-Research-Course-Project-1/blame/master/PA1_template.md">Blame</a>
      <a rel="nofollow" class="btn btn-sm BtnGroup-item" href="/Natasha-R/Reproducible-Research-Course-Project-1/commits/master/PA1_template.md">History</a>
    </div>


    <div>
          <a class="btn-octicon tooltipped tooltipped-nw js-remove-unless-platform"
             data-platforms="windows,mac"
             href="https://desktop.github.com"
             aria-label="Open this file in GitHub Desktop"
             data-ga-click="Repository, open with desktop">
              <svg class="octicon octicon-device-desktop" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M15 2H1c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h5.34c-.25.61-.86 1.39-2.34 2h8c-1.48-.61-2.09-1.39-2.34-2H15c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm0 9H1V3h14v8z"/></svg>
          </a>

          <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="inline-form js-update-url-with-hash" action="/Natasha-R/Reproducible-Research-Course-Project-1/edit/master/PA1_template.md" accept-charset="UTF-8" method="post"><input type="hidden" name="authenticity_token" value="lO5EGTr3z02II5EnUFtRrjo0PtnP09tnGMGE1LY+dZxPTUdPtz1YIojO5bmwyAGrkm8wXQGG1hFtMDplmwkZsg==" />
            <button class="btn-octicon tooltipped tooltipped-nw" type="submit"
              aria-label="Edit the file in your fork of this project" data-hotkey="e" data-disable-with>
              <svg class="octicon octicon-pencil" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 011.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"/></svg>
            </button>
</form>
          <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="inline-form" action="/Natasha-R/Reproducible-Research-Course-Project-1/delete/master/PA1_template.md" accept-charset="UTF-8" method="post"><input type="hidden" name="authenticity_token" value="EwFW5g/50ESqXp6fZfEZZRhV0WckMHphLZrq74FzSrCPUVYuzKPSd++AiytD5B9vEPAhWJRT+/bBuQc4y9D3vA==" />
            <button class="btn-octicon btn-octicon-danger tooltipped tooltipped-nw" type="submit"
              aria-label="Delete the file in your fork of this project" data-disable-with>
              <svg class="octicon octicon-trashcan" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"/></svg>
            </button>
</form>    </div>
  </div>
</div>




      
  <div id="readme" class="Box-body readme blob js-code-block-container">
    <article class="markdown-body entry-content p-3 p-md-6" itemprop="text"><table data-table-type="yaml-metadata">
  <thead>
  <tr>
  <th>title</th>
  <th>output</th>
  </tr>
  </thead>
  <tbody>
  <tr>
  <td><div>Reproducible Research: Peer Assessment 1</div></td>
  <td><div><table>
  <thead>
  <tr>
  <th>html_document</th>
  </tr>
  </thead>
  <tbody>
  <tr>
  <td><div><table>
  <thead>
  <tr>
  <th>keep_md</th>
  </tr>
  </thead>
  <tbody>
  <tr>
  <td><div>true</div></td>
  </tr>
  </tbody>
</table>
</div></td>
  </tr>
  </tbody>
</table>
</div></td>
  </tr>
  </tbody>
</table>

<h2><a id="user-content-introduction" class="anchor" aria-hidden="true" href="#introduction"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Introduction</h2>
<p>This is an R Markdown document, created for the Coursera course "Reproducible Research", in completion of "Peer Assessment 1". The assignment requires students to write an R markdown document evidencing literate programming, using markdown and R programming techniques. There are 5 primary questions to be answered, dealing with processing and analysing data. The data provided to be worked upon, is called "activity monitoring data".</p>
<h3><a id="user-content-the-data" class="anchor" aria-hidden="true" href="#the-data"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>The Data</h3>
<p>The data provided for use, is derived from a study whereupon a single individual wore a "personal activity monitoring device". The study says that:</p>
<blockquote>
<p>"[Activity monitoring devices] are part of the “quantified self” movement – a group of enthusiasts who take measurements about themselves regularly to improve their health, to find patterns in their behavior, or because they are tech geeks. But these data remain under-utilized both because the raw data are hard to obtain and there is a lack of statistical methods and software for processing and interpreting the data."</p>
</blockquote>
<p>The device used in this particular data set collects data on the number of steps taken by an individual, in 5 minute intervals. Two months of data, October/November 2012 are included within the data set. The variables measured include steps (the number of steps taken), date (the day on which the steps measurement was taken) and interval, (the interval in which the steps measurement was taken.) The data is stored in csv format, with 17,598 observations and the aforementioned 3 variables recorded.</p>
<h2><a id="user-content-completing-the-assignment" class="anchor" aria-hidden="true" href="#completing-the-assignment"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Completing the Assignment</h2>
<h3><a id="user-content-question-1-loading-and-preprocessing-the-data" class="anchor" aria-hidden="true" href="#question-1-loading-and-preprocessing-the-data"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Question 1: Loading and preprocessing the data</h3>
<p>The data must be in the user's current working directory for the code to run correctly. The unzip function extracts the data from the zip file, before it is read into R. The object classes contained within each of the variables are defined, so as to speed up the reading process.</p>
<div class="highlight highlight-source-r"><pre>unzip(<span class="pl-s"><span class="pl-pds">"</span>activity.zip<span class="pl-pds">"</span></span>)
<span class="pl-smi">initialData</span> <span class="pl-k">&lt;-</span> read.csv(<span class="pl-s"><span class="pl-pds">"</span>activity.csv<span class="pl-pds">"</span></span>, <span class="pl-v">colClasses</span><span class="pl-k">=</span>c(<span class="pl-s"><span class="pl-pds">"</span>numeric<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>Date<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>numeric<span class="pl-pds">"</span></span>))</pre></div>
<p>An initial look at the data confirms its dimensions and contents.</p>
<div class="highlight highlight-source-r"><pre>head(<span class="pl-smi">initialData</span>)</pre></div>
<pre><code>##   steps       date interval
## 1    NA 2012-10-01        0
## 2    NA 2012-10-01        5
## 3    NA 2012-10-01       10
## 4    NA 2012-10-01       15
## 5    NA 2012-10-01       20
## 6    NA 2012-10-01       25
</code></pre>
<div class="highlight highlight-source-r"><pre>str(<span class="pl-smi">initialData</span>)</pre></div>
<pre><code>## 'data.frame':	17568 obs. of  3 variables:
##  $ steps   : num  NA NA NA NA NA NA NA NA NA NA ...
##  $ date    : Date, format: "2012-10-01" "2012-10-01" ...
##  $ interval: num  0 5 10 15 20 25 30 35 40 45 ...
</code></pre>
<h3><a id="user-content-question-2-what-is-mean-total-number-of-steps-taken-per-day" class="anchor" aria-hidden="true" href="#question-2-what-is-mean-total-number-of-steps-taken-per-day"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Question 2: What is mean total number of steps taken per day?</h3>
<p>The question states any missing values in the data set can be ignored. From using the summary functions previously, it is already known that there are NA values within the steps variable, so these can be removed now.</p>
<div class="highlight highlight-source-r"><pre><span class="pl-smi">data</span> <span class="pl-k">&lt;-</span> <span class="pl-smi">initialData</span>[<span class="pl-k">!</span>(is.na(<span class="pl-smi">initialData</span><span class="pl-k">$</span><span class="pl-smi">steps</span>)), ]</pre></div>
<p>To calculate the total number of steps taken per day, the data first needs to be grouped separately for each day, and then the sum of each group calculated. The aggregate function can complete both of these steps, and format the output in a tidy data frame.</p>
<div class="highlight highlight-source-r"><pre><span class="pl-smi">totalStepsDay</span> <span class="pl-k">&lt;-</span> aggregate(<span class="pl-smi">steps</span> <span class="pl-k">~</span> <span class="pl-smi">date</span>, <span class="pl-smi">data</span>, <span class="pl-smi">sum</span>)
head(<span class="pl-smi">totalStepsDay</span>)</pre></div>
<pre><code>##         date steps
## 1 2012-10-02   126
## 2 2012-10-03 11352
## 3 2012-10-04 12116
## 4 2012-10-05 13294
## 5 2012-10-06 15420
## 6 2012-10-07 11015
</code></pre>
<p>Creating exploratory plots are useful to be able to quickly see a view of all of the data, and pick out any potential patterns. Here, a histogram is created to indicate the frequency of total steps taken each day.</p>
<div class="highlight highlight-source-r"><pre><span class="pl-smi">paletteBlue</span> <span class="pl-k">&lt;-</span> colorRampPalette(c(<span class="pl-s"><span class="pl-pds">"</span>skyblue<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>darkblue<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>skyblue<span class="pl-pds">"</span></span>))
hist(<span class="pl-smi">totalStepsDay</span><span class="pl-k">$</span><span class="pl-smi">steps</span>, <span class="pl-v">breaks</span><span class="pl-k">=</span><span class="pl-c1">20</span>, <span class="pl-v">xlab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Number of Steps Taken<span class="pl-pds">"</span></span>, 
     <span class="pl-v">main</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Histogram of the Total Number of Steps Taken per Day<span class="pl-pds">"</span></span>,
     <span class="pl-v">col</span><span class="pl-k">=</span>paletteBlue(<span class="pl-c1">22</span>), <span class="pl-v">family</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>serif<span class="pl-pds">"</span></span>)</pre></div>
<p><a target="_blank" rel="noopener noreferrer" href="/Natasha-R/Reproducible-Research-Course-Project-1/blob/master/figure/unnamed-chunk-5-1.png"><img src="/Natasha-R/Reproducible-Research-Course-Project-1/raw/master/figure/unnamed-chunk-5-1.png" alt="plot of chunk unnamed-chunk-5" style="max-width:100%;"></a></p>
<p>Finally, the summarise function can calculate the mean and median values of the total number of steps taken per day.</p>
<div class="highlight highlight-source-r"><pre>library(<span class="pl-smi">dplyr</span>)
<span class="pl-smi">totalStepsSummary</span> <span class="pl-k">&lt;-</span> summarise(<span class="pl-smi">totalStepsDay</span>, <span class="pl-v">meanOfTotalSteps</span><span class="pl-k">=</span>mean(<span class="pl-smi">totalStepsDay</span><span class="pl-k">$</span><span class="pl-smi">steps</span>),
                               <span class="pl-v">medianOfTotalSteps</span><span class="pl-k">=</span>median(<span class="pl-smi">totalStepsDay</span><span class="pl-k">$</span><span class="pl-smi">steps</span>))
print(<span class="pl-smi">totalStepsSummary</span>)</pre></div>
<pre><code>##   meanOfTotalSteps medianOfTotalSteps
## 1         10766.19              10765
</code></pre>
<p>Therefore the mean value calculated is <strong>10766.19</strong>, and the median value <strong>10765</strong>.</p>
<h3><a id="user-content-question-3-what-is-the-average-daily-activity-pattern" class="anchor" aria-hidden="true" href="#question-3-what-is-the-average-daily-activity-pattern"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Question 3: What is the average daily activity pattern?</h3>
<p>To look at the average daily pattern, we can use another exploratory graph, this time a time series plot. As this plot should look at the average number of steps taken for each interval, (utilising all days), the aggregate function must be used again, to split the data into groups for each interval, and then averaged with the mean function.</p>
<div class="highlight highlight-source-r"><pre><span class="pl-smi">meanStepsInterval</span> <span class="pl-k">&lt;-</span> aggregate(<span class="pl-smi">steps</span> <span class="pl-k">~</span> <span class="pl-smi">interval</span>, <span class="pl-smi">data</span>, <span class="pl-smi">mean</span>)
head(<span class="pl-smi">meanStepsInterval</span>)</pre></div>
<pre><code>##   interval     steps
## 1        0 1.7169811
## 2        5 0.3396226
## 3       10 0.1320755
## 4       15 0.1509434
## 5       20 0.0754717
## 6       25 2.0943396
</code></pre>
<p>The base R plotting system is used to create a time series plot, with each interval on the x axis, and the average steps data on the y axis.</p>
<div class="highlight highlight-source-r"><pre>plot(<span class="pl-v">x</span><span class="pl-k">=</span><span class="pl-smi">meanStepsInterval</span><span class="pl-k">$</span><span class="pl-smi">interval</span>, <span class="pl-v">y</span><span class="pl-k">=</span><span class="pl-smi">meanStepsInterval</span><span class="pl-k">$</span><span class="pl-smi">steps</span>, <span class="pl-v">type</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>l<span class="pl-pds">"</span></span>,
     <span class="pl-v">main</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Time Series Plot of Average Steps Taken per Interval<span class="pl-pds">"</span></span>,
     <span class="pl-v">ylab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Number of Steps<span class="pl-pds">"</span></span>, <span class="pl-v">xlab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Intervals (in 5 mins)<span class="pl-pds">"</span></span>,
     <span class="pl-v">col</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>darkblue<span class="pl-pds">"</span></span>, <span class="pl-v">lwd</span><span class="pl-k">=</span><span class="pl-c1">1.5</span>, <span class="pl-v">family</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>serif<span class="pl-pds">"</span></span>)</pre></div>
<p><a target="_blank" rel="noopener noreferrer" href="/Natasha-R/Reproducible-Research-Course-Project-1/blob/master/figure/unnamed-chunk-8-1.png"><img src="/Natasha-R/Reproducible-Research-Course-Project-1/raw/master/figure/unnamed-chunk-8-1.png" alt="plot of chunk unnamed-chunk-8" style="max-width:100%;"></a></p>
<p>The last part of this question asks "which five minute interval contains the maximum number of steps?" To answer this the max function can be used, which prints out the maximum value from a numeric vector.</p>
<div class="highlight highlight-source-r"><pre><span class="pl-smi">meanStepsInterval</span>[grep(max(<span class="pl-smi">meanStepsInterval</span><span class="pl-k">$</span><span class="pl-smi">steps</span>), <span class="pl-smi">meanStepsInterval</span><span class="pl-k">$</span><span class="pl-smi">steps</span>), ]</pre></div>
<pre><code>##     interval    steps
## 104      835 206.1698
</code></pre>
<p>So the interval with the maximum number of steps is interval <strong>835</strong>.</p>
<h3><a id="user-content-question-4-imputing-missing-values" class="anchor" aria-hidden="true" href="#question-4-imputing-missing-values"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Question 4: Imputing missing values</h3>
<p>As the data can be confirmed to contain some NA values as some of the observations:</p>
<div class="highlight highlight-source-r"><pre>anyNA(<span class="pl-smi">initialData</span>)</pre></div>
<pre><code>## [1] TRUE
</code></pre>
<p>It is necessary to find out whether the NA values are more-so clustered to one area within the data. Looking at each of the variables:</p>
<div class="highlight highlight-source-r"><pre><span class="pl-k">data.frame</span>(<span class="pl-v">steps</span><span class="pl-k">=</span>sum(is.na(<span class="pl-smi">initialData</span><span class="pl-k">$</span><span class="pl-smi">steps</span>)), 
           <span class="pl-v">interval</span><span class="pl-k">=</span>sum(is.na(<span class="pl-smi">initialData</span><span class="pl-k">$</span><span class="pl-smi">interval</span>)), 
           <span class="pl-v">date</span><span class="pl-k">=</span>sum(is.na(<span class="pl-smi">initialData</span><span class="pl-k">$</span><span class="pl-smi">date</span>)))</pre></div>
<pre><code>##   steps interval date
## 1  2304        0    0
</code></pre>
<p>It can be seen that all 2304 NA values are contained within the steps variable.</p>
<p>Therefore an imputing strategy must be devised to replace all of these missing values with usable numeric measurements. To do so, I decided to replace each missing value with the mean value for the same interval, averaged across all days.</p>
<p>I used a for loop to achieve this, first testing if each observation was an NA value, and if so, replacing it with the mean average for that interval, (as calculated in a previous question).</p>
<div class="highlight highlight-source-r"><pre><span class="pl-smi">imputedData</span> <span class="pl-k">&lt;-</span> <span class="pl-smi">initialData</span>
<span class="pl-k">for</span>(<span class="pl-smi">x</span> <span class="pl-k">in</span> <span class="pl-c1">1</span><span class="pl-k">:</span><span class="pl-c1">17568</span>) {
    <span class="pl-k">if</span>(is.na(<span class="pl-smi">imputedData</span>[<span class="pl-smi">x</span>, <span class="pl-c1">1</span>])<span class="pl-k">==</span><span class="pl-c1">TRUE</span>) {
        <span class="pl-smi">imputedData</span>[<span class="pl-smi">x</span>, <span class="pl-c1">1</span>] <span class="pl-k">&lt;-</span> <span class="pl-smi">meanStepsInterval</span>[<span class="pl-smi">meanStepsInterval</span><span class="pl-k">$</span><span class="pl-smi">interval</span> <span class="pl-k">%in%</span> <span class="pl-smi">imputedData</span>[<span class="pl-smi">x</span>, <span class="pl-c1">3</span>], <span class="pl-c1">2</span>]
    }
}
head(<span class="pl-smi">imputedData</span>)</pre></div>
<pre><code>##       steps       date interval
## 1 1.7169811 2012-10-01        0
## 2 0.3396226 2012-10-01        5
## 3 0.1320755 2012-10-01       10
## 4 0.1509434 2012-10-01       15
## 5 0.0754717 2012-10-01       20
## 6 2.0943396 2012-10-01       25
</code></pre>
<p>Now that the NA values have been replaced, a histogram from the imputed data can be created. This histogram should indicate the frequency of the total number of steps taken per day. Therefore again, the data must be grouped and "summed" by day.</p>
<div class="highlight highlight-source-r"><pre><span class="pl-smi">imputedTotalStepsDay</span> <span class="pl-k">&lt;-</span> aggregate(<span class="pl-smi">steps</span> <span class="pl-k">~</span> <span class="pl-smi">date</span>, <span class="pl-smi">imputedData</span>, <span class="pl-smi">sum</span>)
head(<span class="pl-smi">imputedTotalStepsDay</span>)</pre></div>
<pre><code>##         date    steps
## 1 2012-10-01 10766.19
## 2 2012-10-02   126.00
## 3 2012-10-03 11352.00
## 4 2012-10-04 12116.00
## 5 2012-10-05 13294.00
## 6 2012-10-06 15420.00
</code></pre>
<p>Creating the histogram:</p>
<div class="highlight highlight-source-r"><pre><span class="pl-smi">paletteRed</span> <span class="pl-k">&lt;-</span> colorRampPalette(c(<span class="pl-s"><span class="pl-pds">"</span>deeppink<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>darkred<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>deeppink<span class="pl-pds">"</span></span>))
hist(<span class="pl-smi">imputedTotalStepsDay</span><span class="pl-k">$</span><span class="pl-smi">steps</span>, <span class="pl-v">breaks</span><span class="pl-k">=</span><span class="pl-c1">20</span>, <span class="pl-v">xlab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Number of Steps Taken<span class="pl-pds">"</span></span>, 
     <span class="pl-v">main</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Histogram of Total Number of Steps Taken per Day (With Imputed Values)<span class="pl-pds">"</span></span>,
     <span class="pl-v">col</span><span class="pl-k">=</span>paletteRed(<span class="pl-c1">22</span>), <span class="pl-v">family</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>serif<span class="pl-pds">"</span></span>)</pre></div>
<p><a target="_blank" rel="noopener noreferrer" href="/Natasha-R/Reproducible-Research-Course-Project-1/blob/master/figure/unnamed-chunk-14-1.png"><img src="/Natasha-R/Reproducible-Research-Course-Project-1/raw/master/figure/unnamed-chunk-14-1.png" alt="plot of chunk unnamed-chunk-14" style="max-width:100%;"></a></p>
<p>The question then asks for calculation of the mean and median total number of steps taken per day, which can be calculated using the summarise function.</p>
<div class="highlight highlight-source-r"><pre><span class="pl-smi">imputedStepsSummary</span> <span class="pl-k">&lt;-</span> summarise(<span class="pl-smi">imputedTotalStepsDay</span>, 
                                 <span class="pl-v">meanOfTotalSteps</span><span class="pl-k">=</span>mean(<span class="pl-smi">imputedTotalStepsDay</span><span class="pl-k">$</span><span class="pl-smi">steps</span>), 
                                 <span class="pl-v">medianOfTotalSteps</span><span class="pl-k">=</span>median(<span class="pl-smi">imputedTotalStepsDay</span><span class="pl-k">$</span><span class="pl-smi">steps</span>))  
print(<span class="pl-smi">imputedStepsSummary</span>)</pre></div>
<pre><code>##   meanOfTotalSteps medianOfTotalSteps
## 1         10766.19           10766.19
</code></pre>
<p>This a similar calculation to the one completed at the start of the assignment, (without the imputed values,) and thus they can be compared.</p>
<div class="highlight highlight-source-r"><pre>rbind(<span class="pl-smi">totalStepsSummary</span>, <span class="pl-smi">imputedTotalStepsSummary</span>)</pre></div>
<pre><code>##   meanOfTotalSteps medianOfTotalSteps
## 1         10766.19           10765.00
## 2         10766.19           10766.19
</code></pre>
<p>The values of the two data sets are very similar, if not exactly the same, due to the use of averaging functions when imputing the NA measurements. The mean values are the same, at <strong>10766.19</strong> steps, while the median value is slightly larger for the imputed data set, at <strong>10766.19</strong> steps, rather than <strong>10765</strong> steps.</p>
<p>If histograms of the two data sets (imputed and non-imputed) are compared:</p>
<div class="highlight highlight-source-r"><pre>par(<span class="pl-v">mfrow</span> <span class="pl-k">=</span> c(<span class="pl-c1">1</span>, <span class="pl-c1">2</span>))

hist(<span class="pl-smi">totalStepsDay</span><span class="pl-k">$</span><span class="pl-smi">steps</span>, <span class="pl-v">breaks</span><span class="pl-k">=</span><span class="pl-c1">20</span>, <span class="pl-v">xlab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Number of Steps Taken<span class="pl-pds">"</span></span>, 
     <span class="pl-v">col</span><span class="pl-k">=</span>paletteBlue(<span class="pl-c1">22</span>), <span class="pl-v">family</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>serif<span class="pl-pds">"</span></span>, <span class="pl-v">ylim</span><span class="pl-k">=</span>c(<span class="pl-c1">0</span>, <span class="pl-c1">20</span>), <span class="pl-v">main</span><span class="pl-k">=</span><span class="pl-c1">NULL</span>)
hist(<span class="pl-smi">imputedTotalStepsDay</span><span class="pl-k">$</span><span class="pl-smi">steps</span>, <span class="pl-v">breaks</span><span class="pl-k">=</span><span class="pl-c1">20</span>, <span class="pl-v">xlab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Number of Steps Taken<span class="pl-pds">"</span></span>, 
     <span class="pl-v">col</span><span class="pl-k">=</span>paletteRed(<span class="pl-c1">22</span>), <span class="pl-v">family</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>serif<span class="pl-pds">"</span></span>, <span class="pl-v">ylim</span><span class="pl-k">=</span>c(<span class="pl-c1">0</span>, <span class="pl-c1">20</span>), <span class="pl-v">main</span><span class="pl-k">=</span><span class="pl-c1">NULL</span>)
mtext(<span class="pl-s"><span class="pl-pds">"</span>Histograms of Total Number of Steps Taken per Day, Without/With Imputed Values<span class="pl-pds">"</span></span>,
      <span class="pl-v">adj</span><span class="pl-k">=</span><span class="pl-c1">0.95</span>, <span class="pl-v">family</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>serif<span class="pl-pds">"</span></span>, <span class="pl-v">font</span><span class="pl-k">=</span><span class="pl-c1">2</span>)</pre></div>
<p><a target="_blank" rel="noopener noreferrer" href="/Natasha-R/Reproducible-Research-Course-Project-1/blob/master/figure/unnamed-chunk-17-1.png"><img src="/Natasha-R/Reproducible-Research-Course-Project-1/raw/master/figure/unnamed-chunk-17-1.png" alt="plot of chunk unnamed-chunk-17" style="max-width:100%;"></a></p>
<p>It can be seen that the frequency of values increases in the second histogram, which is expected, due to the imputed values.</p>
<p>More explanations for the differences between the non and imputed data sets can be seen by looking at the NA values grouped by their date variable.</p>
<div class="highlight highlight-source-r"><pre><span class="pl-smi">naByDate</span> <span class="pl-k">&lt;-</span> <span class="pl-smi">initialData</span>[is.na(<span class="pl-smi">initialData</span><span class="pl-k">$</span><span class="pl-smi">steps</span>), ]
table(<span class="pl-smi">naByDate</span><span class="pl-k">$</span><span class="pl-smi">date</span>)</pre></div>
<pre><code>## 
## 2012-10-01 2012-10-08 2012-11-01 2012-11-04 2012-11-09 2012-11-10 
##        288        288        288        288        288        288 
## 2012-11-14 2012-11-30 
##        288        288
</code></pre>
<p>As there are exactly 288 intervals measured for each day:</p>
<div class="highlight highlight-source-r"><pre>length(unique(<span class="pl-smi">data</span><span class="pl-k">$</span><span class="pl-smi">interval</span>))</pre></div>
<pre><code>## [1] 288
</code></pre>
<p>It is therefore shown by the above table, that in the initial data set, missing observations are due to entirely missed days, (8 of the days) where no measurements were made whatsoever. This therefore reinforces that the imputing technique used, of utilising average interval data, was likely more useful than potentially using average daily data.</p>
<h3><a id="user-content-question-5-are-there-differences-in-activity-patterns-between-weekdays-and-weekends" class="anchor" aria-hidden="true" href="#question-5-are-there-differences-in-activity-patterns-between-weekdays-and-weekends"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Question 5: Are there differences in activity patterns between weekdays and weekends?</h3>
<p>The question indicates that the imputed data set should be used to answer this problem.<br>
To help in answering this question, firstly a new factor variable should be created within the data frame. This should indicate whether each day is a "weekday" or a "weekend".</p>
<p>To achieve this, I used the weekdays function to automatically calculate the day of the week each day resided upon, (Monday, Tuesday, etc.) Next, I wrote a for loop, which would assign the factor value "weekend" to all rows it read as having the values "Saturday" or "Sunday", and assign "weekday" to the others.</p>
<div class="highlight highlight-source-r"><pre><span class="pl-smi">daysData</span> <span class="pl-k">&lt;-</span> <span class="pl-smi">imputedData</span>
<span class="pl-smi">daysData</span><span class="pl-k">$</span><span class="pl-smi">days</span> <span class="pl-k">&lt;-</span> weekdays(<span class="pl-smi">daysData</span><span class="pl-k">$</span><span class="pl-smi">date</span>)
<span class="pl-smi">daysData</span><span class="pl-k">$</span><span class="pl-smi">weekday</span> <span class="pl-k">&lt;-</span> as.character(rep(<span class="pl-c1">0</span>, <span class="pl-v">times</span><span class="pl-k">=</span><span class="pl-c1">17568</span>))
<span class="pl-k">for</span>(<span class="pl-smi">x</span> <span class="pl-k">in</span> <span class="pl-c1">1</span><span class="pl-k">:</span><span class="pl-c1">17568</span>) {
    <span class="pl-k">if</span>(<span class="pl-smi">daysData</span>[<span class="pl-smi">x</span>, <span class="pl-c1">4</span>] <span class="pl-k">%in%</span> c(<span class="pl-s"><span class="pl-pds">"</span>Saturday<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>Sunday<span class="pl-pds">"</span></span>)) {
        <span class="pl-smi">daysData</span>[<span class="pl-smi">x</span>, <span class="pl-c1">5</span>] <span class="pl-k">&lt;-</span> <span class="pl-s"><span class="pl-pds">"</span>weekend<span class="pl-pds">"</span></span>
    } <span class="pl-k">else</span> {
        <span class="pl-smi">daysData</span>[<span class="pl-smi">x</span>, <span class="pl-c1">5</span>] <span class="pl-k">&lt;-</span> <span class="pl-s"><span class="pl-pds">"</span>weekday<span class="pl-pds">"</span></span>
    }
}
<span class="pl-smi">daysData</span><span class="pl-k">$</span><span class="pl-smi">weekday</span> <span class="pl-k">&lt;-</span> <span class="pl-k">factor</span>(<span class="pl-smi">daysData</span><span class="pl-k">$</span><span class="pl-smi">weekday</span>)
head(<span class="pl-smi">daysData</span>)</pre></div>
<pre><code>##       steps       date interval   days weekday
## 1 1.7169811 2012-10-01        0 Monday weekday
## 2 0.3396226 2012-10-01        5 Monday weekday
## 3 0.1320755 2012-10-01       10 Monday weekday
## 4 0.1509434 2012-10-01       15 Monday weekday
## 5 0.0754717 2012-10-01       20 Monday weekday
## 6 2.0943396 2012-10-01       25 Monday weekday
</code></pre>
<p>To compare the weekday and weekend data, and create two plots of the average number of steps taken per interval, the data has to be split into two groups of weekday/weekend data, using the newly created variable.</p>
<div class="highlight highlight-source-r"><pre><span class="pl-smi">weekdayData</span> <span class="pl-k">&lt;-</span> <span class="pl-smi">daysData</span>[<span class="pl-smi">daysData</span><span class="pl-k">$</span><span class="pl-smi">weekday</span><span class="pl-k">==</span><span class="pl-s"><span class="pl-pds">"</span>weekday<span class="pl-pds">"</span></span>, ]
<span class="pl-smi">weekendData</span> <span class="pl-k">&lt;-</span> <span class="pl-smi">daysData</span>[<span class="pl-smi">daysData</span><span class="pl-k">$</span><span class="pl-smi">weekday</span><span class="pl-k">==</span><span class="pl-s"><span class="pl-pds">"</span>weekend<span class="pl-pds">"</span></span>, ]</pre></div>
<p>Next, the average number of steps per interval is calculated, much like it has been done in previous questions.</p>
<div class="highlight highlight-source-r"><pre><span class="pl-smi">weekdayMean</span> <span class="pl-k">&lt;-</span> aggregate(<span class="pl-smi">steps</span> <span class="pl-k">~</span> <span class="pl-smi">interval</span>, <span class="pl-smi">weekdayData</span>, <span class="pl-smi">mean</span>)
<span class="pl-smi">weekendMean</span> <span class="pl-k">&lt;-</span> aggregate(<span class="pl-smi">steps</span> <span class="pl-k">~</span> <span class="pl-smi">interval</span>, <span class="pl-smi">weekendData</span>, <span class="pl-smi">mean</span>)</pre></div>
<p>Finally the panel plot is created. The x axis indicates each 5 minute interval, and the y axis shows the average number of steps taken. The two plots are divided into weekday, and weekend data.</p>
<div class="highlight highlight-source-r"><pre>par(<span class="pl-v">mfrow</span><span class="pl-k">=</span>c(<span class="pl-c1">2</span>, <span class="pl-c1">1</span>), <span class="pl-v">mar</span><span class="pl-k">=</span>c(<span class="pl-c1">4</span>, <span class="pl-c1">4.1</span>, <span class="pl-c1">3</span>, <span class="pl-c1">2.1</span>))
plot(<span class="pl-smi">weekdayMean</span><span class="pl-k">$</span><span class="pl-smi">interval</span>, <span class="pl-smi">weekdayMean</span><span class="pl-k">$</span><span class="pl-smi">steps</span>, <span class="pl-v">type</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>l<span class="pl-pds">"</span></span>,
     <span class="pl-v">main</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Time Series Plot of Average Steps Taken per Interval, for Weekdays<span class="pl-pds">"</span></span>,
     <span class="pl-v">xlab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Intervals (in 5 mins)<span class="pl-pds">"</span></span>, <span class="pl-v">ylab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Number of Steps<span class="pl-pds">"</span></span>, <span class="pl-v">family</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>serif<span class="pl-pds">"</span></span>,
     <span class="pl-v">col</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>darkred<span class="pl-pds">"</span></span>, <span class="pl-v">lwd</span><span class="pl-k">=</span><span class="pl-c1">1.5</span>, <span class="pl-v">ylim</span><span class="pl-k">=</span>c(<span class="pl-c1">0</span>, <span class="pl-c1">230</span>))
plot(<span class="pl-smi">weekendMean</span><span class="pl-k">$</span><span class="pl-smi">interval</span>, <span class="pl-smi">weekendMean</span><span class="pl-k">$</span><span class="pl-smi">steps</span>, <span class="pl-v">type</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>l<span class="pl-pds">"</span></span>,
     <span class="pl-v">main</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Time Series Plot of Average Steps Taken per Interval, for Weekends<span class="pl-pds">"</span></span>,
     <span class="pl-v">xlab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Intervals (in 5 mins)<span class="pl-pds">"</span></span>, <span class="pl-v">ylab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Number of Steps<span class="pl-pds">"</span></span>, <span class="pl-v">family</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>serif<span class="pl-pds">"</span></span>,
     <span class="pl-v">col</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>darkblue<span class="pl-pds">"</span></span>, <span class="pl-v">lwd</span><span class="pl-k">=</span><span class="pl-c1">1.5</span>, <span class="pl-v">ylim</span><span class="pl-k">=</span>c(<span class="pl-c1">0</span>, <span class="pl-c1">230</span>))</pre></div>
<p><a target="_blank" rel="noopener noreferrer" href="/Natasha-R/Reproducible-Research-Course-Project-1/blob/master/figure/unnamed-chunk-23-1.png"><img src="/Natasha-R/Reproducible-Research-Course-Project-1/raw/master/figure/unnamed-chunk-23-1.png" alt="plot of chunk unnamed-chunk-23" style="max-width:100%;"></a></p>
</article>
  </div>

    </div>

  

  <details class="details-reset details-overlay details-overlay-dark">
    <summary data-hotkey="l" aria-label="Jump to line"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast linejump" aria-label="Jump to line">
      <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-jump-to-line-form Box-body d-flex" action="" accept-charset="UTF-8" method="get">
        <input class="form-control flex-auto mr-3 linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
        <button type="submit" class="btn" data-close-dialog>Go</button>
</form>    </details-dialog>
  </details>



  </div>
</div>

    </main>
  </div>
  

  </div>

        
<div class="footer container-lg width-full p-responsive" role="contentinfo">
  <div class="position-relative d-flex flex-row-reverse flex-lg-row flex-wrap flex-lg-nowrap flex-justify-center flex-lg-justify-between pt-6 pb-2 mt-6 f6 text-gray border-top border-gray-light ">
    <ul class="list-style-none d-flex flex-wrap col-12 col-lg-5 flex-justify-center flex-lg-justify-between mb-2 mb-lg-0">
      <li class="mr-3 mr-lg-0">&copy; 2020 GitHub, Inc.</li>
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to terms, text:terms" href="https://github.com/site/terms">Terms</a></li>
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to privacy, text:privacy" href="https://github.com/site/privacy">Privacy</a></li>
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to security, text:security" href="https://github.com/security">Security</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://githubstatus.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a data-ga-click="Footer, go to help, text:help" href="https://help.github.com">Help</a></li>

    </ul>

    <a aria-label="Homepage" title="GitHub" class="footer-octicon d-none d-lg-block mx-lg-4" href="https://github.com">
      <svg height="24" class="octicon octicon-mark-github" viewBox="0 0 16 16" version="1.1" width="24" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"/></svg>
</a>
   <ul class="list-style-none d-flex flex-wrap col-12 col-lg-5 flex-justify-center flex-lg-justify-between mb-2 mb-lg-0">
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to contact, text:contact" href="https://github.com/contact">Contact GitHub</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://github.com/pricing" data-ga-click="Footer, go to Pricing, text:Pricing">Pricing</a></li>
      <li class="mr-3 mr-lg-0"><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li class="mr-3 mr-lg-0"><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://github.blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a data-ga-click="Footer, go to about, text:about" href="https://github.com/about">About</a></li>
    </ul>
  </div>
  <div class="d-flex flex-justify-center pb-6">
    <span class="f6 text-gray-light"></span>
  </div>
</div>



  <div id="ajax-error-message" class="ajax-error-message flash flash-error">
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.893 1.5c-.183-.31-.52-.5-.887-.5s-.703.19-.886.5L.138 13.499a.98.98 0 000 1.001c.193.31.53.501.886.501h13.964c.367 0 .704-.19.877-.5a1.03 1.03 0 00.01-1.002L8.893 1.5zm.133 11.497H6.987v-2.003h2.039v2.003zm0-3.004H6.987V5.987h2.039v4.006z"/></svg>
    <button type="button" class="flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
      <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
    </button>
    You can’t perform that action at this time.
  </div>


    <script crossorigin="anonymous" async="async" integrity="sha512-o4vS4IKrjdy/HD+xr2+VhO6DxQmj5jikhHbEGrd8+JGhpmIOxRrpT1Qo5k3IhKimm8VXIu3pyYejLtOAkm+OsQ==" type="application/javascript" id="js-conditional-compat" data-src="https://github.githubassets.com/assets/compat-bootstrap-a38bd2e0.js"></script>
    <script crossorigin="anonymous" async="async" integrity="sha512-3yNijdFdVDBZQDWrBvMeD2J9gyXwI5MKUMJSWdEGP44DgS4NEPQw2TmVlDdNAWrseJO5C/sXBSTrL24DvGMDJw==" type="application/javascript" src="https://github.githubassets.com/assets/vendor-df23628d.js"></script>
    <script crossorigin="anonymous" integrity="sha512-ozTuLK+weMb2+KN3YYEKu49kNfx9NYwIQ4XNRS0uHdeEg1p8wQiJ4iUVfagDqYNdLHALZNdQKfTsscDoZx6GIQ==" type="application/javascript" src="https://github.githubassets.com/assets/frameworks-a334ee2c.js"></script>
    
    <script crossorigin="anonymous" async="async" integrity="sha512-igDa5qJY+BfsXAWSgEJ2KyM1xLcTE6V/z/YpOL+rA23jLJ5IrHHv7G5gUUIBNSc0X5wFpks8Fb5oT+kTLwdOTw==" type="application/javascript" src="https://github.githubassets.com/assets/github-bootstrap-8a00dae6.js"></script>
    
    
    
  <div class="js-stale-session-flash flash flash-warn flash-banner" hidden
    >
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.893 1.5c-.183-.31-.52-.5-.887-.5s-.703.19-.886.5L.138 13.499a.98.98 0 000 1.001c.193.31.53.501.886.501h13.964c.367 0 .704-.19.877-.5a1.03 1.03 0 00.01-1.002L8.893 1.5zm.133 11.497H6.987v-2.003h2.039v2.003zm0-3.004H6.987V5.987h2.039v4.006z"/></svg>
    <span class="js-stale-session-flash-signed-in" hidden>You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
    <span class="js-stale-session-flash-signed-out" hidden>You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
  </div>
  <template id="site-details-dialog">
  <details class="details-reset details-overlay details-overlay-dark lh-default text-gray-dark hx_rsm" open>
    <summary role="button" aria-label="Close dialog"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast hx_rsm-dialog hx_rsm-modal">
      <button class="Box-btn-octicon m-0 btn-octicon position-absolute right-0 top-0" type="button" aria-label="Close dialog" data-close-dialog>
        <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
      </button>
      <div class="octocat-spinner my-6 js-details-dialog-spinner"></div>
    </details-dialog>
  </details>
</template>

  <div class="Popover js-hovercard-content position-absolute" style="display: none; outline: none;" tabindex="0">
  <div class="Popover-message Popover-message--bottom-left Popover-message--large Box box-shadow-large" style="width:360px;">
  </div>
</div>

  <div aria-live="polite" class="js-global-screen-reader-notice sr-only"></div>

  </body>
</html>

