





<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
  <link rel="dns-prefetch" href="https://assets-cdn.github.com">
  <link rel="dns-prefetch" href="https://avatars0.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars1.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars2.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars3.githubusercontent.com">
  <link rel="dns-prefetch" href="https://github-cloud.s3.amazonaws.com">
  <link rel="dns-prefetch" href="https://user-images.githubusercontent.com/">



  <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/frameworks-63d382b7c748b0ca1b0b8772c6ac07942f39a78775d4716abded6fb8d6d8e544845848ef5f69e923c6e897cace3a187cd55e75ef1f78a58dd410b2e609b6673a.css" integrity="sha512-Y9OCt8dIsMobC4dyxqwHlC85p4d11HFqve1vuNbY5USEWEjvX2npI8bol8rOOhh81V517x94pY3UELLmCbZnOg==" media="all" rel="stylesheet" />
  <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github-f8fdb60cff0b8b931a0fbab9ed7fd288db4ab05af5a99310d6503f0f5650b8332b4ed54c8dab22c027ce351be82acfb34824e9dbbde0ce768fd5ae3477d819c6.css" integrity="sha512-+P22DP8Li5MaD7q57X/SiNtKsFr1qZMQ1lA/D1ZQuDMrTtVMjasiwCfONRvoKs+zSCTp273gznaP1a40d9gZxg==" media="all" rel="stylesheet" />
  
  
  
  

  <meta name="viewport" content="width=device-width">
  
  <title>d3-ease/README.md at master · d3/d3-ease</title>
  <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
  <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
  <meta property="fb:app_id" content="1401488693436528">

    
    <meta content="https://avatars3.githubusercontent.com/u/1562726?s=400&amp;v=4" property="og:image" /><meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="d3/d3-ease" property="og:title" /><meta content="https://github.com/d3/d3-ease" property="og:url" /><meta content="d3-ease - Easing functions for smooth animation." property="og:description" />

  <link rel="assets" href="https://assets-cdn.github.com/">
  <link rel="web-socket" href="wss://live.github.com/_sockets/VjI6MjM0MjAxNjIzOjhmYmJjNWRmMzI1MGQ0ZDkxN2JkZTNiYjg2ODdmZGViMGJhOTJmODE5M2IwZTIzOGQ5Njc3MjdkN2M0NjQyZTE=--e863a2791ede6f1da9979c48b10c7934d948604e">
  <meta name="pjax-timeout" content="1000">
  <link rel="sudo-modal" href="/sessions/sudo_modal">
  <meta name="request-id" content="F902:1FA0E:119A97E:198E7A1:5A603DF1" data-pjax-transient>
  

  <meta name="selected-link" value="repo_source" data-pjax-transient>

    <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
  <meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
  <meta name="google-site-verification" content="GXs5KoUUkNCoaAZn7wPN-t01Pywp9M3sEjnt_3_ZWPc">
    <meta name="google-analytics" content="UA-3769691-2">

<meta content="collector.githubapp.com" name="octolytics-host" /><meta content="github" name="octolytics-app-id" /><meta content="https://collector.githubapp.com/github-external/browser_event" name="octolytics-event-url" /><meta content="F902:1FA0E:119A97E:198E7A1:5A603DF1" name="octolytics-dimension-request_id" /><meta content="sea" name="octolytics-dimension-region_edge" /><meta content="iad" name="octolytics-dimension-region_render" /><meta content="16659379" name="octolytics-actor-id" /><meta content="xswei" name="octolytics-actor-login" /><meta content="72a8b786cd27412ba348c71058cf2aed3e8f8772266e5c157980395250fb923d" name="octolytics-actor-hash" />
<meta content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" name="analytics-location" />




  <meta class="js-ga-set" name="dimension1" content="Logged In">


  

      <meta name="hostname" content="github.com">
  <meta name="user-login" content="xswei">

      <meta name="expected-hostname" content="github.com">
    <meta name="js-proxy-site-detection-payload" content="MDY5MzM5NzNiOGMwN2QzYzFmNGIxNTYxODhmMGQwMDFlZWQ0ZjEzYzcwM2U0YjM5OGNjYWM2ZDM0MDUyOWQ1YXx7InJlbW90ZV9hZGRyZXNzIjoiMjIwLjE4MS4xNzEuMTI1IiwicmVxdWVzdF9pZCI6IkY5MDI6MUZBMEU6MTE5QTk3RToxOThFN0ExOjVBNjAzREYxIiwidGltZXN0YW1wIjoxNTE2MjU2NzU1LCJob3N0IjoiZ2l0aHViLmNvbSJ9">

    <meta name="enabled-features" content="UNIVERSE_BANNER,FREE_TRIALS">

  <meta name="html-safe-nonce" content="95ac36701972faaa3306c820d3f61fe703aeac54">

  <meta http-equiv="x-pjax-version" content="c0275ff3857f879afa7c0ef3fbc951b4">
  

      <link href="https://github.com/d3/d3-ease/commits/master.atom" rel="alternate" title="Recent Commits to d3-ease:master" type="application/atom+xml">

  <meta name="description" content="d3-ease - Easing functions for smooth animation.">
  <meta name="go-import" content="github.com/d3/d3-ease git https://github.com/d3/d3-ease.git">

  <meta content="1562726" name="octolytics-dimension-user_id" /><meta content="d3" name="octolytics-dimension-user_login" /><meta content="36697270" name="octolytics-dimension-repository_id" /><meta content="d3/d3-ease" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="36697270" name="octolytics-dimension-repository_network_root_id" /><meta content="d3/d3-ease" name="octolytics-dimension-repository_network_root_nwo" /><meta content="false" name="octolytics-dimension-repository_explore_github_marketplace_ci_cta_shown" />


    <link rel="canonical" href="https://github.com/d3/d3-ease/blob/master/README.md" data-pjax-transient>


  <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">

  <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">

  <link rel="mask-icon" href="https://assets-cdn.github.com/pinned-octocat.svg" color="#000000">
  <link rel="icon" type="image/x-icon" class="js-site-favicon" href="https://assets-cdn.github.com/favicon.ico">

<meta name="theme-color" content="#1e2327">


  <meta name="u2f-support" content="true">

  </head>

  <body class="logged-in env-production page-blob">
    

  <div class="position-relative js-header-wrapper ">
    <a href="#start-of-content" tabindex="1" class="bg-black text-white p-3 show-on-focus js-skip-to-content">Skip to content</a>
    <div id="js-pjax-loader-bar" class="pjax-loader-bar"><div class="progress"></div></div>

    
    
    



        
<header class="Header  f5" role="banner">
  <div class="d-flex px-3 flex-justify-between container-lg">
    <div class="d-flex flex-justify-between">
      <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <svg aria-hidden="true" class="octicon octicon-mark-github" height="32" version="1.1" viewBox="0 0 16 16" width="32"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>


    </div>

    <div class="HeaderMenu d-flex flex-justify-between flex-auto">
      <div class="d-flex">
            <div class="">
              <div class="header-search scoped-search site-scoped-search js-site-search" role="search">
  <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/d3/d3-ease/search" class="js-site-search-form" data-scoped-search-url="/d3/d3-ease/search" data-unscoped-search-url="/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <label class="form-control header-search-wrapper js-chromeless-input-container">
        <a href="/d3/d3-ease/blob/master/README.md" class="header-search-scope no-underline">This repository</a>
      <input type="text"
        class="form-control header-search-input js-site-search-focus js-site-search-field is-clearable"
        data-hotkey="s"
        name="q"
        value=""
        placeholder="Search"
        aria-label="Search this repository"
        data-unscoped-placeholder="Search GitHub"
        data-scoped-placeholder="Search"
        autocapitalize="off">
        <input type="hidden" class="js-site-search-type-field" name="type" >
    </label>
</form></div>

            </div>

          <ul class="d-flex pl-2 flex-items-center text-bold list-style-none" role="navigation">
            <li>
              <a href="/pulls" aria-label="Pull requests you created" class="js-selected-navigation-item HeaderNavlink px-2" data-ga-click="Header, click, Nav menu - item:pulls context:user" data-hotkey="g p" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls">
                Pull requests
</a>            </li>
            <li>
              <a href="/issues" aria-label="Issues you created" class="js-selected-navigation-item HeaderNavlink px-2" data-ga-click="Header, click, Nav menu - item:issues context:user" data-hotkey="g i" data-selected-links="/issues /issues/assigned /issues/mentioned /issues">
                Issues
</a>            </li>
                <li>
                  <a href="/marketplace" class="js-selected-navigation-item HeaderNavlink px-2" data-ga-click="Header, click, Nav menu - item:marketplace context:user" data-selected-links=" /marketplace">
                    Marketplace
</a>                </li>
            <li>
              <a href="/explore" class="js-selected-navigation-item HeaderNavlink px-2" data-ga-click="Header, click, Nav menu - item:explore" data-selected-links="/explore /trending /trending/developers /integrations /integrations/feature/code /integrations/feature/collaborate /integrations/feature/ship showcases showcases_search showcases_landing /explore">
                Explore
</a>            </li>
          </ul>
      </div>

      <div class="d-flex">
        
<ul class="user-nav d-flex flex-items-center list-style-none" id="user-links">
  <li class="dropdown js-menu-container">
    <span class="d-inline-block  px-2">
      

    </span>
  </li>

  <li class="dropdown js-menu-container">
    <details class="dropdown-details details-reset js-dropdown-details d-flex px-2 flex-items-center">
      <summary class="HeaderNavlink"
         aria-label="Create new…"
         data-ga-click="Header, create new, icon:add">
        <svg aria-hidden="true" class="octicon octicon-plus float-left mr-1 mt-1" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 9H7v5H5V9H0V7h5V2h2v5h5z"/></svg>
        <span class="dropdown-caret mt-1"></span>
      </summary>

      <ul class="dropdown-menu dropdown-menu-sw">
        
<a class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>

  <a class="dropdown-item" href="/new/import" data-ga-click="Header, import a repository">
    Import repository
  </a>

<a class="dropdown-item" href="https://gist.github.com/" data-ga-click="Header, create new gist">
  New gist
</a>

  <a class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>



  <div class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="d3/d3-ease">This repository</span>
  </div>
    <a class="dropdown-item" href="/d3/d3-ease/issues/new" data-ga-click="Header, create new issue">
      New issue
    </a>

      </ul>
    </details>
  </li>

  <li class="dropdown js-menu-container">

    <details class="dropdown-details details-reset js-dropdown-details d-flex pl-2 flex-items-center">
      <summary class="HeaderNavlink name mt-1"
        aria-label="View profile and more"
        data-ga-click="Header, show menu, icon:avatar">
        <img alt="@xswei" class="avatar float-left mr-1" src="https://avatars0.githubusercontent.com/u/16659379?s=40&amp;v=4" height="20" width="20">
        <span class="dropdown-caret"></span>
      </summary>

      <ul class="dropdown-menu dropdown-menu-sw">
        <li class="dropdown-header header-nav-current-user css-truncate">
          Signed in as <strong class="css-truncate-target">xswei</strong>
        </li>

        <li class="dropdown-divider"></li>

        <li><a class="dropdown-item" href="/xswei" data-ga-click="Header, go to profile, text:your profile">
          Your profile
        </a></li>
        <li><a class="dropdown-item" href="/xswei?tab=stars" data-ga-click="Header, go to starred repos, text:your stars">
          Your stars
        </a></li>
          <li><a class="dropdown-item" href="https://gist.github.com/" data-ga-click="Header, your gists, text:your gists">Your Gists</a></li>

        <li class="dropdown-divider"></li>

        <li><a class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">
          Help
        </a></li>

        <li><a class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">
          Settings
        </a></li>

        <li><!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/logout" class="logout-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="WXbIGSeDai/OhW41p8+qIpB6L5KwXxmgySwig7gECenHEExsbITeo7XVvLVQXNKS0zbSx+in72h7WB0h+awIlw==" /></div>
          <button type="submit" class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
            Sign out
          </button>
        </form></li>
      </ul>
    </details>
  </li>
</ul>


        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/logout" class="sr-only right-0" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="9u7ckEnm0GCyUQCmowkfwnMl9bIT69hVoXTq4KHRvcdoiFjlAuFk7MkB0iZUmmdyMGkI50sTLp0TANVC4Hm8uQ==" /></div>
          <button type="submit" class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
            Sign out
          </button>
</form>      </div>
    </div>
  </div>
</header>

      

  </div>

  <div id="start-of-content" class="show-on-focus"></div>

    <div id="js-flash-container">
</div>



  <div role="main" >
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode" class="">
    <div id="js-repo-pjax-container" data-pjax-container >
      




  



  <div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav  ">
    <div class="repohead-details-container clearfix container">

      <ul class="pagehead-actions">
  <li>
        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="UgzeV5f/EFY27HgnOdbHO9bBnfHtLqQUeN6FlYW1TEQ/5Z1HcD6iEA0z/q1j7FFAVFqw17PTmiZaJbvG7uhACw==" /></div>      <input class="form-control" id="repository_id" name="repository_id" type="hidden" value="36697270" />

        <div class="select-menu js-menu-container js-select-menu">
          <a href="/d3/d3-ease/subscription"
            class="btn btn-sm btn-with-count select-menu-button js-menu-target"
            role="button"
            aria-haspopup="true"
            aria-expanded="false"
            aria-label="Toggle repository notifications menu"
            data-ga-click="Repository, click Watch settings, action:blob#show">
            <span class="js-select-button">
                <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                Watch
            </span>
          </a>
          <a class="social-count js-social-count"
            href="/d3/d3-ease/watchers"
            aria-label="17 users are watching this repository">
            17
          </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content">
            <div class="select-menu-header js-navigation-enable" tabindex="-1">
              <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
              <span class="select-menu-title">Notifications</span>
            </div>

              <div class="select-menu-list js-navigation-container" role="menu">

                <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
                  <div class="select-menu-item-text">
                    <input checked="checked" id="do_included" name="do" type="radio" value="included" />
                    <span class="select-menu-item-heading">Not watching</span>
                    <span class="description">Be notified when participating or @mentioned.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                      Watch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
                  <div class="select-menu-item-text">
                    <input id="do_subscribed" name="do" type="radio" value="subscribed" />
                    <span class="select-menu-item-heading">Watching</span>
                    <span class="description">Be notified of all conversations.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                        Unwatch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
                  <div class="select-menu-item-text">
                    <input id="do_ignore" name="do" type="radio" value="ignore" />
                    <span class="select-menu-item-heading">Ignoring</span>
                    <span class="description">Never be notified.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-mute" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8 2.81v10.38c0 .67-.81 1-1.28.53L3 10H1c-.55 0-1-.45-1-1V7c0-.55.45-1 1-1h2l3.72-3.72C7.19 1.81 8 2.14 8 2.81zm7.53 3.22l-1.06-1.06-1.97 1.97-1.97-1.97-1.06 1.06L11.44 8 9.47 9.97l1.06 1.06 1.97-1.97 1.97 1.97 1.06-1.06L13.56 8l1.97-1.97z"/></svg>
                        Stop ignoring
                    </span>
                  </div>
                </div>

              </div>

            </div>
          </div>
        </div>
</form>
  </li>

  <li>
    
  <div class="js-toggler-container js-social-container starring-container ">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/d3/d3-ease/unstar" class="starred js-social-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="ZKKpE+2dzqRIotCx2UU7yVnOTAMdmTsz5VgX+se4DRQd02FvNZrt1uwbg5q4LpaaZZZ3fDgKL7jcUiGnb4KpjQ==" /></div>
      <input type="hidden" name="context" value="repository"></input>
      <button
        type="submit"
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar d3/d3-ease"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74z"/></svg>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/d3/d3-ease/stargazers"
           aria-label="288 users starred this repository">
          288
        </a>
</form>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/d3/d3-ease/star" class="unstarred js-social-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="eP8m+iw6XP0MbYSl8Lkd88rDqf8fIM3GqbJBLJFRwbT/RzBvbIxqOZEubPyez0eprRsLOD/nzqXLx2LKT/YNCw==" /></div>
      <input type="hidden" name="context" value="repository"></input>
      <button
        type="submit"
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star d3/d3-ease"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74z"/></svg>
        Star
      </button>
        <a class="social-count js-social-count" href="/d3/d3-ease/stargazers"
           aria-label="288 users starred this repository">
          288
        </a>
</form>  </div>

  </li>

  <li>
          <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/d3/d3-ease/fork" class="btn-with-count" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="W2y3vCTC+TPw+ctEwafDw7CFtLF8oEVdFXtDrTVAZhjnE5mZhrO0aEHBCcPpwv34y1d+Y+OcdrrMpK8HSvJARA==" /></div>
            <button
                type="submit"
                class="btn btn-sm btn-with-count"
                data-ga-click="Repository, show fork modal, action:blob#show; text:Fork"
                title="Fork your own copy of d3/d3-ease to your account"
                aria-label="Fork your own copy of d3/d3-ease to your account">
              <svg aria-hidden="true" class="octicon octicon-repo-forked" height="16" version="1.1" viewBox="0 0 10 16" width="10"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 0 0-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 0 0 2 1a1.993 1.993 0 0 0-1 3.72V6.5l3 3v1.78A1.993 1.993 0 0 0 5 15a1.993 1.993 0 0 0 1-3.72V9.5l3-3V4.72A1.993 1.993 0 0 0 8 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
              Fork
            </button>
</form>
    <a href="/d3/d3-ease/network" class="social-count"
       aria-label="23 users forked this repository">
      23
    </a>
  </li>
</ul>

      <h1 class="public ">
  <svg aria-hidden="true" class="octicon octicon-repo" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
  <span class="author" itemprop="author"><a href="/d3" class="url fn" rel="author">d3</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a href="/d3/d3-ease" data-pjax="#js-repo-pjax-container">d3-ease</a></strong>

</h1>

    </div>
    
<nav class="reponav js-repo-nav js-sidenav-container-pjax container"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
     role="navigation"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/d3/d3-ease" class="js-selected-navigation-item selected reponav-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /d3/d3-ease" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-code" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"/></svg>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a href="/d3/d3-ease/issues" class="js-selected-navigation-item reponav-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /d3/d3-ease/issues" itemprop="url">
        <svg aria-hidden="true" class="octicon octicon-issue-opened" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M7 2.3c3.14 0 5.7 2.56 5.7 5.7s-2.56 5.7-5.7 5.7A5.71 5.71 0 0 1 1.3 8c0-3.14 2.56-5.7 5.7-5.7zM7 1C3.14 1 0 4.14 0 8s3.14 7 7 7 7-3.14 7-7-3.14-7-7-7zm1 3H6v5h2V4zm0 6H6v2h2v-2z"/></svg>
        <span itemprop="name">Issues</span>
        <span class="Counter">3</span>
        <meta itemprop="position" content="2">
</a>    </span>

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/d3/d3-ease/pulls" class="js-selected-navigation-item reponav-item" data-hotkey="g p" data-selected-links="repo_pulls /d3/d3-ease/pulls" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-git-pull-request" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0 0 10 15a1.993 1.993 0 0 0 1-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 0 0-1 3.72v6.56A1.993 1.993 0 0 0 2 15a1.993 1.993 0 0 0 1-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
      <span itemprop="name">Pull requests</span>
      <span class="Counter">0</span>
      <meta itemprop="position" content="3">
</a>  </span>




  <a href="/d3/d3-ease/pulse" class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors dependency_graph pulse /d3/d3-ease/pulse">
    <svg aria-hidden="true" class="octicon octicon-graph" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"/></svg>
    Insights
</a>

</nav>


  </div>

<div class="container new-discussion-timeline experiment-repo-nav ">
  <div class="repository-content ">

    
  <a href="/d3/d3-ease/blob/f1e8d630b58f5b935b7995f0c417de257b08be52/README.md" class="d-none js-permalink-shortcut" data-hotkey="y">Permalink</a>

  <!-- blob contrib key: blob_contributors:v21:dfde9283c539e5274207d6c31fa07c7e -->

  <div class="file-navigation js-zeroclipboard-container">
    
<div class="select-menu branch-select-menu js-menu-container js-select-menu float-left">
  <button class=" btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    
    type="button" aria-label="Switch branches or tags" aria-expanded="false" aria-haspopup="true">
      <i>Branch:</i>
      <span class="js-select-button css-truncate-target">master</span>
  </button>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax>

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
        <span class="select-menu-title">Switch branches/tags</span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="form-control js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Filter branches/tags" class="js-select-menu-tab" role="tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab" role="tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches" role="menu">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/d3/d3-ease/blob/interface/README.md"
               data-name="interface"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                interface
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/d3/d3-ease/blob/master/README.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                master
              </span>
            </a>
        </div>

          <div class="select-menu-no-results">Nothing to show</div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/d3/d3-ease/tree/v1.0.3/README.md"
              data-name="v1.0.3"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v1.0.3">
                v1.0.3
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/d3/d3-ease/tree/v1.0.2/README.md"
              data-name="v1.0.2"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v1.0.2">
                v1.0.2
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/d3/d3-ease/tree/v1.0.1/README.md"
              data-name="v1.0.1"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v1.0.1">
                v1.0.1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/d3/d3-ease/tree/v1.0.0/README.md"
              data-name="v1.0.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v1.0.0">
                v1.0.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/d3/d3-ease/tree/v0.8.0/README.md"
              data-name="v0.8.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v0.8.0">
                v0.8.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/d3/d3-ease/tree/v0.7.0/README.md"
              data-name="v0.7.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v0.7.0">
                v0.7.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/d3/d3-ease/tree/v0.6.0/README.md"
              data-name="v0.6.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v0.6.0">
                v0.6.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/d3/d3-ease/tree/v0.5.2/README.md"
              data-name="v0.5.2"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v0.5.2">
                v0.5.2
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/d3/d3-ease/tree/v0.5.1/README.md"
              data-name="v0.5.1"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v0.5.1">
                v0.5.1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/d3/d3-ease/tree/v0.5.0/README.md"
              data-name="v0.5.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v0.5.0">
                v0.5.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/d3/d3-ease/tree/v0.4.0/README.md"
              data-name="v0.4.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v0.4.0">
                v0.4.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/d3/d3-ease/tree/v0.3.1/README.md"
              data-name="v0.3.1"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v0.3.1">
                v0.3.1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/d3/d3-ease/tree/v0.3.0/README.md"
              data-name="v0.3.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v0.3.0">
                v0.3.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/d3/d3-ease/tree/v0.2.1/README.md"
              data-name="v0.2.1"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v0.2.1">
                v0.2.1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/d3/d3-ease/tree/v0.2.0/README.md"
              data-name="v0.2.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v0.2.0">
                v0.2.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/d3/d3-ease/tree/v0.1.5/README.md"
              data-name="v0.1.5"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v0.1.5">
                v0.1.5
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/d3/d3-ease/tree/v0.1.4/README.md"
              data-name="v0.1.4"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v0.1.4">
                v0.1.4
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/d3/d3-ease/tree/v0.1.3/README.md"
              data-name="v0.1.3"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v0.1.3">
                v0.1.3
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/d3/d3-ease/tree/v0.1.2/README.md"
              data-name="v0.1.2"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v0.1.2">
                v0.1.2
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/d3/d3-ease/tree/v0.1.1/README.md"
              data-name="v0.1.1"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v0.1.1">
                v0.1.1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/d3/d3-ease/tree/v0.1.0/README.md"
              data-name="v0.1.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v0.1.0">
                v0.1.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/d3/d3-ease/tree/v0.0.2/README.md"
              data-name="v0.0.2"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v0.0.2">
                v0.0.2
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/d3/d3-ease/tree/v0.0.1/README.md"
              data-name="v0.0.1"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v0.0.1">
                v0.0.1
              </span>
            </a>
        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div>

    </div>
  </div>
</div>

    <div class="BtnGroup float-right">
      <a href="/d3/d3-ease/find/master"
            class="js-pjax-capture-input btn btn-sm BtnGroup-item"
            data-pjax
            data-hotkey="t">
        Find file
      </a>
      <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm BtnGroup-item tooltipped tooltipped-s" data-copied-hint="Copied!" type="button">Copy path</button>
    </div>
    <div class="breadcrumb js-zeroclipboard-target">
      <span class="repo-root js-repo-root"><span class="js-path-segment"><a href="/d3/d3-ease"><span>d3-ease</span></a></span></span><span class="separator">/</span><strong class="final-path">README.md</strong>
    </div>
  </div>


  
  <div class="commit-tease">
      <span class="float-right">
        <a class="commit-tease-sha" href="/d3/d3-ease/commit/b76b0024b8eb82bac4696c1fb6c43b8a3dbf2152" data-pjax>
          b76b002
        </a>
        <relative-time datetime="2016-08-12T14:32:09Z">Aug 12, 2016</relative-time>
      </span>
      <div>
        <img alt="@Devinsuit" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/11741306?s=40&amp;v=4" width="20" />
        <a href="/Devinsuit" class="user-mention" rel="contributor">Devinsuit</a>
          <a href="/d3/d3-ease/commit/b76b0024b8eb82bac4696c1fb6c43b8a3dbf2152" class="message" data-pjax="true" title="Add links to source">Add links to source</a>
      </div>

    <div class="commit-tease-contributors">
      <button type="button" class="btn-link muted-link contributors-toggle" data-facebox="#blob_contributors_box">
        <strong>2</strong>
         contributors
      </button>
          <a class="avatar-link tooltipped tooltipped-s" aria-label="mbostock" href="/d3/d3-ease/commits/master/README.md?author=mbostock"><img alt="@mbostock" class="avatar" height="20" src="https://avatars1.githubusercontent.com/u/230541?s=40&amp;v=4" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="Devinsuit" href="/d3/d3-ease/commits/master/README.md?author=Devinsuit"><img alt="@Devinsuit" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/11741306?s=40&amp;v=4" width="20" /> </a>


    </div>

    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header" data-facebox-id="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list" data-facebox-id="facebox-description">
          <li class="facebox-user-list-item">
            <img alt="@mbostock" height="24" src="https://avatars0.githubusercontent.com/u/230541?s=48&amp;v=4" width="24" />
            <a href="/mbostock">mbostock</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@Devinsuit" height="24" src="https://avatars1.githubusercontent.com/u/11741306?s=48&amp;v=4" width="24" />
            <a href="/Devinsuit">Devinsuit</a>
          </li>
      </ul>
    </div>
  </div>


  <div class="file">
    <div class="file-header">
  <div class="file-actions">

    <div class="BtnGroup">
      <a href="/d3/d3-ease/raw/master/README.md" class="btn btn-sm BtnGroup-item" id="raw-url">Raw</a>
        <a href="/d3/d3-ease/blame/master/README.md" class="btn btn-sm js-update-url-with-hash BtnGroup-item" data-hotkey="b">Blame</a>
      <a href="/d3/d3-ease/commits/master/README.md" class="btn btn-sm BtnGroup-item" rel="nofollow">History</a>
    </div>

        <a class="btn-octicon tooltipped tooltipped-nw"
           href="github-windows://openRepo/https://github.com/d3/d3-ease?branch=master&amp;filepath=README.md"
           aria-label="Open this file in GitHub Desktop"
           data-ga-click="Repository, open with desktop, type:windows">
            <svg aria-hidden="true" class="octicon octicon-device-desktop" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M15 2H1c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h5.34c-.25.61-.86 1.39-2.34 2h8c-1.48-.61-2.09-1.39-2.34-2H15c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm0 9H1V3h14v8z"/></svg>
        </a>

          <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/d3/d3-ease/edit/master/README.md" class="inline-form js-update-url-with-hash" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="ULpIEVmtoU5oK6/qPNLxlbMK8379GhmaNTyJy5JSQyt0PbrKdoDe27rVz4fbh67lTISr/6xMLfdC2+AnQNQQng==" /></div>
            <button class="btn-octicon tooltipped tooltipped-nw" type="submit"
              aria-label="Fork this project and edit the file" data-hotkey="e" data-disable-with>
              <svg aria-hidden="true" class="octicon octicon-pencil" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 0 1 1.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"/></svg>
            </button>
</form>
        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/d3/d3-ease/delete/master/README.md" class="inline-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="ZMQtob0dUAwchfYmN18NGy42Qd4qBdVpze0pCu1qX2FKXCB+3aV77tCtYfJ28k+Led59uqJnDyP4bwRBk5oAhg==" /></div>
          <button class="btn-octicon btn-octicon-danger tooltipped tooltipped-nw" type="submit"
            aria-label="Fork this project and delete the file" data-disable-with>
            <svg aria-hidden="true" class="octicon octicon-trashcan" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"/></svg>
          </button>
</form>  </div>

  <div class="file-info">
      242 lines (132 sloc)
      <span class="file-info-divider"></span>
    17.4 KB
  </div>
</div>

    
  <div id="readme" class="readme blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="text"><h1><a href="#d3-ease" aria-hidden="true" class="anchor" id="user-content-d3-ease"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>d3-ease</h1>
<p><em>Easing</em> is a method of distorting time to control apparent motion in animation. It is most commonly used for <a href="https://en.wikipedia.org/wiki/12_basic_principles_of_animation#Slow_In_and_Slow_Out" rel="nofollow">slow-in, slow-out</a>. By easing time, <a href="https://github.com/d3/d3-transition">animated transitions</a> are smoother and exhibit more plausible motion.</p>
<p>The easing types in this module implement the <a href="#ease_ease">ease method</a>, which takes a normalized time <em>t</em> and returns the corresponding “eased” time <em>tʹ</em>. Both the normalized time and the eased time are typically in the range [0,1], where 0 represents the start of the animation and 1 represents the end; some easing types, such as <a href="#easeElastic">elastic</a>, may return eased times slightly outside this range. A good easing type should return 0 if <em>t</em> = 0 and 1 if <em>t</em> = 1. See the <a href="http://bl.ocks.org/mbostock/248bac3b8e354a9103c4" rel="nofollow">easing explorer</a> for a visual demonstration.</p>
<p>These easing types are largely based on work by <a href="http://robertpenner.com/easing/" rel="nofollow">Robert Penner</a>.</p>
<h2><a href="#installing" aria-hidden="true" class="anchor" id="user-content-installing"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Installing</h2>
<p>If you use NPM, <code>npm install d3-ease</code>. Otherwise, download the <a href="https://github.com/d3/d3-ease/releases/latest">latest release</a>. You can also load directly from <a href="https://d3js.org" rel="nofollow">d3js.org</a>, either as a <a href="https://d3js.org/d3-ease.v1.min.js" rel="nofollow">standalone library</a> or as part of <a href="https://github.com/d3/d3">D3 4.0</a>. AMD, CommonJS, and vanilla environments are supported. In vanilla, a <code>d3</code> global is exported:</p>
<div class="highlight highlight-text-html-basic"><pre>&lt;<span class="pl-ent">script</span> <span class="pl-e">src</span>=<span class="pl-s"><span class="pl-pds">"</span>https://d3js.org/d3-ease.v1.min.js<span class="pl-pds">"</span></span>&gt;&lt;/<span class="pl-ent">script</span>&gt;
&lt;<span class="pl-ent">script</span>&gt;<span class="pl-s1"></span>
<span class="pl-s1"></span>
<span class="pl-s1"><span class="pl-k">var</span> ease <span class="pl-k">=</span> <span class="pl-smi">d3</span>.<span class="pl-smi">easeCubic</span>;</span>
<span class="pl-s1"></span>
<span class="pl-s1"></span><span class="pl-s1">&lt;</span>/<span class="pl-ent">script</span>&gt;</pre></div>
<p><a href="https://tonicdev.com/npm/d3-ease" rel="nofollow">Try d3-ease in your browser.</a></p>
<h2><a href="#api-reference" aria-hidden="true" class="anchor" id="user-content-api-reference"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>API Reference</h2>
<p><a name="user-content-_ease" href="#_ease">#</a> <i>ease</i>(<i>t</i>)</p>
<p>Given the specified normalized time <em>t</em>, typically in the range [0,1], returns the “eased” time <em>tʹ</em>, also typically in [0,1]. 0 represents the start of the animation and 1 represents the end. A good implementation returns 0 if <em>t</em> = 0 and 1 if <em>t</em> = 1. See the <a href="http://bl.ocks.org/mbostock/248bac3b8e354a9103c4" rel="nofollow">easing explorer</a> for a visual demonstration. For example, to apply <a href="#easeCubic">cubic</a> easing:</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">var</span> te <span class="pl-k">=</span> <span class="pl-smi">d3</span>.<span class="pl-en">easeCubic</span>(t);</pre></div>
<p>Similarly, to apply custom <a href="#easeElastic">elastic</a> easing:</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> Before the animation starts, create your easing function.</span>
<span class="pl-k">var</span> customElastic <span class="pl-k">=</span> <span class="pl-smi">d3</span>.<span class="pl-smi">easeElastic</span>.<span class="pl-en">period</span>(<span class="pl-c1">0.4</span>);

<span class="pl-c"><span class="pl-c">//</span> During the animation, apply the easing function.</span>
<span class="pl-k">var</span> te <span class="pl-k">=</span> <span class="pl-en">customElastic</span>(t);</pre></div>
<p><a name="user-content-easeLinear" href="#easeLinear">#</a> d3.<b>easeLinear</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/linear.js" title="Source">&lt;&gt;</a></p>
<p>Linear easing; the identity function; <em>linear</em>(<em>t</em>) returns <em>t</em>.</p>
<p><a href="http://bl.ocks.org/mbostock/248bac3b8e354a9103c4/#linear" rel="nofollow"><img src="https://raw.githubusercontent.com/d3/d3-ease/master/img/linear.png" alt="linear" width="100%" height="240" style="max-width:100%;"></a></p>
<p><a name="user-content-easePolyIn" href="#easePolyIn">#</a> d3.<b>easePolyIn</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/poly.js#L3" title="Source">&lt;&gt;</a></p>
<p>Polynomial easing; raises <em>t</em> to the specified <a href="#poly_exponent">exponent</a>. If the exponent is not specified, it defaults to 3, equivalent to <a href="#easeCubicIn">cubicIn</a>.</p>
<p><a href="http://bl.ocks.org/mbostock/248bac3b8e354a9103c4/#polyIn" rel="nofollow"><img src="https://raw.githubusercontent.com/d3/d3-ease/master/img/polyIn.png" alt="polyIn" width="100%" height="240" style="max-width:100%;"></a></p>
<p><a name="user-content-easePolyOut" href="#easePolyOut">#</a> d3.<b>easePolyOut</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/poly.js#L15" title="Source">&lt;&gt;</a></p>
<p>Reverse polynomial easing; equivalent to 1 - <a href="#easePolyIn">polyIn</a>(1 - <em>t</em>). If the <a href="#poly_exponent">exponent</a> is not specified, it defaults to 3, equivalent to <a href="#easeCubicOut">cubicOut</a>.</p>
<p><a href="http://bl.ocks.org/mbostock/248bac3b8e354a9103c4/#polyOut" rel="nofollow"><img src="https://raw.githubusercontent.com/d3/d3-ease/master/img/polyOut.png" alt="polyOut" width="100%" height="240" style="max-width:100%;"></a></p>
<p><a name="user-content-easePoly" href="#easePoly">#</a> d3.<b>easePoly</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/poly.js" title="Source">&lt;&gt;</a>
<br><a name="user-content-easePolyInOut" href="#easePolyInOut">#</a> d3.<b>easePolyInOut</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/poly.js#L27" title="Source">&lt;&gt;</a></p>
<p>Symmetric polynomial easing; scales <a href="#easePolyIn">polyIn</a> for <em>t</em> in [0, 0.5] and <a href="#easePolyOut">polyOut</a> for <em>t</em> in [0.5, 1]. If the <a href="#poly_exponent">exponent</a> is not specified, it defaults to 3, equivalent to <a href="#easeCubic">cubic</a>.</p>
<p><a href="http://bl.ocks.org/mbostock/248bac3b8e354a9103c4/#polyInOut" rel="nofollow"><img src="https://raw.githubusercontent.com/d3/d3-ease/master/img/polyInOut.png" alt="polyInOut" width="100%" height="240" style="max-width:100%;"></a></p>
<p><a name="user-content-poly_exponent" href="#poly_exponent">#</a> <i>poly</i>.<b>exponent</b>(<i>e</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/poly.js#L1" title="Source">&lt;&gt;</a></p>
<p>Returns a new polynomial easing with the specified exponent <em>e</em>. For example, to create equivalents of <a href="#easeLinear">linear</a>, <a href="#easeQuad">quad</a>, and <a href="#easeCubic">cubic</a>:</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">var</span> linear <span class="pl-k">=</span> <span class="pl-smi">d3</span>.<span class="pl-smi">easePoly</span>.<span class="pl-en">exponent</span>(<span class="pl-c1">1</span>),
    quad <span class="pl-k">=</span> <span class="pl-smi">d3</span>.<span class="pl-smi">easePoly</span>.<span class="pl-en">exponent</span>(<span class="pl-c1">2</span>),
    cubic <span class="pl-k">=</span> <span class="pl-smi">d3</span>.<span class="pl-smi">easePoly</span>.<span class="pl-en">exponent</span>(<span class="pl-c1">3</span>);</pre></div>
<p><a name="user-content-easeQuadIn" href="#easeQuadIn">#</a> d3.<b>easeQuadIn</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/quad.js#L1" title="Source">&lt;&gt;</a></p>
<p>Quadratic easing; equivalent to <a href="#easePolyIn">polyIn</a>.<a href="#poly_exponent">exponent</a>(2).</p>
<p><a href="http://bl.ocks.org/mbostock/248bac3b8e354a9103c4/#quadIn" rel="nofollow"><img src="https://raw.githubusercontent.com/d3/d3-ease/master/img/quadIn.png" alt="quadIn" width="100%" height="240" style="max-width:100%;"></a></p>
<p><a name="user-content-easeQuadOut" href="#easeQuadOut">#</a> d3.<b>easeQuadOut</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/quad.js#L5" title="Source">&lt;&gt;</a></p>
<p>Reverse quadratic easing; equivalent to 1 - <a href="#easeQuadIn">quadIn</a>(1 - <em>t</em>). Also equivalent to <a href="#easePolyOut">polyOut</a>.<a href="#poly_exponent">exponent</a>(2).</p>
<p><a href="http://bl.ocks.org/mbostock/248bac3b8e354a9103c4/#quadOut" rel="nofollow"><img src="https://raw.githubusercontent.com/d3/d3-ease/master/img/quadOut.png" alt="quadOut" width="100%" height="240" style="max-width:100%;"></a></p>
<p><a name="user-content-easeQuad" href="#easeQuad">#</a> d3.<b>easeQuad</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/quad.js" title="Source">&lt;&gt;</a>
<br><a name="user-content-easeQuadInOut" href="#easeQuadInOut">#</a> d3.<b>easeQuadInOut</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/quad.js#L9" title="Source">&lt;&gt;</a></p>
<p>Symmetric quadratic easing; scales <a href="#easeQuadIn">quadIn</a> for <em>t</em> in [0, 0.5] and <a href="#easeQuadOut">quadOut</a> for <em>t</em> in [0.5, 1]. Also equivalent to <a href="#easePoly">poly</a>.<a href="#poly_exponent">exponent</a>(2).</p>
<p><a href="http://bl.ocks.org/mbostock/248bac3b8e354a9103c4/#quadInOut" rel="nofollow"><img src="https://raw.githubusercontent.com/d3/d3-ease/master/img/quadInOut.png" alt="quadInOut" width="100%" height="240" style="max-width:100%;"></a></p>
<p><a name="user-content-easeCubicIn" href="#easeCubicIn">#</a> d3.<b>easeCubicIn</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/cubic.js#L1" title="Source">&lt;&gt;</a></p>
<p>Cubic easing; equivalent to <a href="#easePolyIn">polyIn</a>.<a href="#poly_exponent">exponent</a>(3).</p>
<p><a href="http://bl.ocks.org/mbostock/248bac3b8e354a9103c4/#cubicIn" rel="nofollow"><img src="https://raw.githubusercontent.com/d3/d3-ease/master/img/cubicIn.png" alt="cubicIn" width="100%" height="240" style="max-width:100%;"></a></p>
<p><a name="user-content-easeCubicOut" href="#easeCubicOut">#</a> d3.<b>easeCubicOut</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/cubic.js#L5" title="Source">&lt;&gt;</a></p>
<p>Reverse cubic easing; equivalent to 1 - <a href="#easeCubicIn">cubicIn</a>(1 - <em>t</em>). Also equivalent to <a href="#easePolyOut">polyOut</a>.<a href="#poly_exponent">exponent</a>(3).</p>
<p><a href="http://bl.ocks.org/mbostock/248bac3b8e354a9103c4/#cubicOut" rel="nofollow"><img src="https://raw.githubusercontent.com/d3/d3-ease/master/img/cubicOut.png" alt="cubicOut" width="100%" height="240" style="max-width:100%;"></a></p>
<p><a name="user-content-easeCubic" href="#easeCubic">#</a> d3.<b>easeCubic</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/cubic.js" title="Source">&lt;&gt;</a>
<br><a name="user-content-easeCubicInOut" href="#easeCubicInOut">#</a> d3.<b>easeCubicInOut</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/cubic.js#L9" title="Source">&lt;&gt;</a></p>
<p>Symmetric cubic easing; scales <a href="#easeCubicIn">cubicIn</a> for <em>t</em> in [0, 0.5] and <a href="#easeCubicOut">cubicOut</a> for <em>t</em> in [0.5, 1]. Also equivalent to <a href="#easePoly">poly</a>.<a href="#poly_exponent">exponent</a>(3).</p>
<p><a href="http://bl.ocks.org/mbostock/248bac3b8e354a9103c4/#cubicInOut" rel="nofollow"><img src="https://raw.githubusercontent.com/d3/d3-ease/master/img/cubicInOut.png" alt="cubicInOut" width="100%" height="240" style="max-width:100%;"></a></p>
<p><a name="user-content-easeSinIn" href="#easeSinIn">#</a> d3.<b>easeSinIn</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/sin.js#L4" title="Source">&lt;&gt;</a></p>
<p>Sinusoidal easing; returns sin(<em>t</em>).</p>
<p><a href="http://bl.ocks.org/mbostock/248bac3b8e354a9103c4/#sinIn" rel="nofollow"><img src="https://raw.githubusercontent.com/d3/d3-ease/master/img/sinIn.png" alt="sinIn" width="100%" height="240" style="max-width:100%;"></a></p>
<p><a name="user-content-easeSinOut" href="#easeSinOut">#</a> d3.<b>easeSinOut</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/sin.js#L8" title="Source">&lt;&gt;</a></p>
<p>Reverse sinusoidal easing; equivalent to 1 - <a href="#easeSinIn">sinIn</a>(1 - <em>t</em>).</p>
<p><a href="http://bl.ocks.org/mbostock/248bac3b8e354a9103c4/#sinOut" rel="nofollow"><img src="https://raw.githubusercontent.com/d3/d3-ease/master/img/sinOut.png" alt="sinOut" width="100%" height="240" style="max-width:100%;"></a></p>
<p><a name="user-content-easeSin" href="#easeSin">#</a> d3.<b>easeSin</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/sin.js" title="Source">&lt;&gt;</a>
<br><a name="user-content-easeSinInOut" href="#easeSinInOut">#</a> d3.<b>easeSinInOut</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/sin.js#L12" title="Source">&lt;&gt;</a></p>
<p>Symmetric sinusoidal easing; scales <a href="#easeSinIn">sinIn</a> for <em>t</em> in [0, 0.5] and <a href="#easeSinOut">sinOut</a> for <em>t</em> in [0.5, 1].</p>
<p><a href="http://bl.ocks.org/mbostock/248bac3b8e354a9103c4/#sinInOut" rel="nofollow"><img src="https://raw.githubusercontent.com/d3/d3-ease/master/img/sinInOut.png" alt="sinInOut" width="100%" height="240" style="max-width:100%;"></a></p>
<p><a name="user-content-easeExpIn" href="#easeExpIn">#</a> d3.<b>easeExpIn</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/exp.js#L1" title="Source">&lt;&gt;</a></p>
<p>Exponential easing; raises 2 to the exponent 10 * (<em>t</em> - 1).</p>
<p><a href="http://bl.ocks.org/mbostock/248bac3b8e354a9103c4/#expIn" rel="nofollow"><img src="https://raw.githubusercontent.com/d3/d3-ease/master/img/expIn.png" alt="expIn" width="100%" height="240" style="max-width:100%;"></a></p>
<p><a name="user-content-easeExpOut" href="#easeExpOut">#</a> d3.<b>easeExpOut</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/exp.js#L5" title="Source">&lt;&gt;</a></p>
<p>Reverse exponential easing; equivalent to 1 - <a href="#easeExpIn">expIn</a>(1 - <em>t</em>).</p>
<p><a href="http://bl.ocks.org/mbostock/248bac3b8e354a9103c4/#expOut" rel="nofollow"><img src="https://raw.githubusercontent.com/d3/d3-ease/master/img/expOut.png" alt="expOut" width="100%" height="240" style="max-width:100%;"></a></p>
<p><a name="user-content-easeExp" href="#easeExp">#</a> d3.<b>easeExp</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/exp.js" title="Source">&lt;&gt;</a>
<br><a name="user-content-easeExpInOut" href="#easeExpInOut">#</a> d3.<b>easeExpInOut</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/exp.js#L9" title="Source">&lt;&gt;</a></p>
<p>Symmetric exponential easing; scales <a href="#easeExpIn">expIn</a> for <em>t</em> in [0, 0.5] and <a href="#easeExpOut">expOut</a> for <em>t</em> in [0.5, 1].</p>
<p><a href="http://bl.ocks.org/mbostock/248bac3b8e354a9103c4/#expInOut" rel="nofollow"><img src="https://raw.githubusercontent.com/d3/d3-ease/master/img/expInOut.png" alt="expInOut" width="100%" height="240" style="max-width:100%;"></a></p>
<p><a name="user-content-easeCircleIn" href="#easeCircleIn">#</a> d3.<b>easeCircleIn</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/circle.js#L1" title="Source">&lt;&gt;</a></p>
<p>Circular easing.</p>
<p><a href="http://bl.ocks.org/mbostock/248bac3b8e354a9103c4/#circleIn" rel="nofollow"><img src="https://raw.githubusercontent.com/d3/d3-ease/master/img/circleIn.png" alt="circleIn" width="100%" height="240" style="max-width:100%;"></a></p>
<p><a name="user-content-easeCircleOut" href="#easeCircleOut">#</a> d3.<b>easeCircleOut</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/circle.js#L5" title="Source">&lt;&gt;</a></p>
<p>Reverse circular easing; equivalent to 1 - <a href="#easeCircleIn">circleIn</a>(1 - <em>t</em>).</p>
<p><a href="http://bl.ocks.org/mbostock/248bac3b8e354a9103c4/#circleOut" rel="nofollow"><img src="https://raw.githubusercontent.com/d3/d3-ease/master/img/circleOut.png" alt="circleOut" width="100%" height="240" style="max-width:100%;"></a></p>
<p><a name="user-content-easeCircle" href="#easeCircle">#</a> d3.<b>easeCircle</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/circle.js" title="Source">&lt;&gt;</a>
<br><a name="user-content-easeCircleInOut" href="#easeCircleInOut">#</a> d3.<b>easeCircleInOut</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/circle.js#L9" title="Source">&lt;&gt;</a></p>
<p>Symmetric circular easing; scales <a href="#easeCircleIn">circleIn</a> for <em>t</em> in [0, 0.5] and <a href="#easeCircleOut">circleOut</a> for <em>t</em> in [0.5, 1].</p>
<p><a href="http://bl.ocks.org/mbostock/248bac3b8e354a9103c4/#circleInOut" rel="nofollow"><img src="https://raw.githubusercontent.com/d3/d3-ease/master/img/circleInOut.png" alt="circleInOut" width="100%" height="240" style="max-width:100%;"></a></p>
<p><a name="user-content-easeElasticIn" href="#easeElasticIn">#</a> d3.<b>easeElasticIn</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/elastic.js#L5" title="Source">&lt;&gt;</a></p>
<p>Elastic easing, like a rubber band. The <a href="#elastic_amplitude">amplitude</a> and <a href="#elastic_period">period</a> of the oscillation are configurable; if not specified, they default to 1 and 0.3, respectively.</p>
<p><a href="http://bl.ocks.org/mbostock/248bac3b8e354a9103c4/#elasticIn" rel="nofollow"><img src="https://raw.githubusercontent.com/d3/d3-ease/master/img/elasticIn.png" alt="elasticIn" width="100%" height="360" style="max-width:100%;"></a></p>
<p><a name="user-content-easeElastic" href="#easeElastic">#</a> d3.<b>easeElastic</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/elastic.js" title="Source">&lt;&gt;</a>
<br><a name="user-content-easeElasticOut" href="#easeElasticOut">#</a> d3.<b>easeElasticOut</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/elastic.js#L18" title="Source">&lt;&gt;</a></p>
<p>Reverse elastic easing; equivalent to 1 - <a href="#easeElasticIn">elasticIn</a>(1 - <em>t</em>).</p>
<p><a href="http://bl.ocks.org/mbostock/248bac3b8e354a9103c4/#elasticOut" rel="nofollow"><img src="https://raw.githubusercontent.com/d3/d3-ease/master/img/elasticOut.png" alt="elasticOut" width="100%" height="360" style="max-width:100%;"></a></p>
<p><a name="user-content-easeElasticInOut" href="#easeElasticInOut">#</a> d3.<b>easeElasticInOut</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/elastic.js#L31" title="Source">&lt;&gt;</a></p>
<p>Symmetric elastic easing; scales <a href="#easeElasticIn">elasticIn</a> for <em>t</em> in [0, 0.5] and <a href="#easeElasticOut">elasticOut</a> for <em>t</em> in [0.5, 1].</p>
<p><a href="http://bl.ocks.org/mbostock/248bac3b8e354a9103c4/#elasticInOut" rel="nofollow"><img src="https://raw.githubusercontent.com/d3/d3-ease/master/img/elasticInOut.png" alt="elasticInOut" width="100%" height="360" style="max-width:100%;"></a></p>
<p><a name="user-content-elastic_amplitude" href="#elastic_amplitude">#</a> <i>elastic</i>.<b>amplitude</b>(<i>a</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/elastic.js#L40" title="Source">&lt;&gt;</a></p>
<p>Returns a new elastic easing with the specified amplitude <em>a</em>.</p>
<p><a name="user-content-elastic_period" href="#elastic_period">#</a> <i>elastic</i>.<b>period</b>(<i>p</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/elastic.js#L41" title="Source">&lt;&gt;</a></p>
<p>Returns a new elastic easing with the specified period <em>p</em>.</p>
<p><a name="user-content-easeBackIn" href="#easeBackIn">#</a> d3.<b>easeBackIn</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/back.js#L3" title="Source">&lt;&gt;</a></p>
<p><a href="https://en.wikipedia.org/wiki/12_basic_principles_of_animation#Anticipation" rel="nofollow">Anticipatory</a> easing, like a dancer bending his knees before jumping off the floor. The degree of <a href="#back_overshoot">overshoot</a> is configurable; it not specified, it defaults to 1.70158.</p>
<p><a href="http://bl.ocks.org/mbostock/248bac3b8e354a9103c4/#backIn" rel="nofollow"><img src="https://raw.githubusercontent.com/d3/d3-ease/master/img/backIn.png" alt="backIn" width="100%" height="300" style="max-width:100%;"></a></p>
<p><a name="user-content-easeBackOut" href="#easeBackOut">#</a> d3.<b>easeBackOut</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/back.js#L15" title="Source">&lt;&gt;</a></p>
<p>Reverse anticipatory easing; equivalent to 1 - <a href="#easeBackIn">backIn</a>(1 - <em>t</em>).</p>
<p><a href="http://bl.ocks.org/mbostock/248bac3b8e354a9103c4/#backOut" rel="nofollow"><img src="https://raw.githubusercontent.com/d3/d3-ease/master/img/backOut.png" alt="backOut" width="100%" height="300" style="max-width:100%;"></a></p>
<p><a name="user-content-easeBack" href="#easeBack">#</a> d3.<b>easeBack</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/back.js" title="Source">&lt;&gt;</a>
<br><a name="user-content-easeBackInOut" href="#easeBackInOut">#</a> d3.<b>easeBackInOut</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/back.js#L27" title="Source">&lt;&gt;</a></p>
<p>Symmetric anticipatory easing; scales <a href="#easeBackIn">backIn</a> for <em>t</em> in [0, 0.5] and <a href="#easeBackOut">backOut</a> for <em>t</em> in [0.5, 1].</p>
<p><a href="http://bl.ocks.org/mbostock/248bac3b8e354a9103c4/#backInOut" rel="nofollow"><img src="https://raw.githubusercontent.com/d3/d3-ease/master/img/backInOut.png" alt="backInOut" width="100%" height="300" style="max-width:100%;"></a></p>
<p><a name="user-content-back_overshoot" href="#back_overshoot">#</a> <i>back</i>.<b>overshoot</b>(<i>s</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/back.js#L1" title="Source">&lt;&gt;</a></p>
<p>Returns a new back easing with the specified overshoot <em>s</em>.</p>
<p><a name="user-content-easeBounceIn" href="#easeBounceIn">#</a> d3.<b>easeBounceIn</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/bounce.js#L12" title="Source">&lt;&gt;</a></p>
<p>Bounce easing, like a rubber ball.</p>
<p><a href="http://bl.ocks.org/mbostock/248bac3b8e354a9103c4/#bounceIn" rel="nofollow"><img src="https://raw.githubusercontent.com/d3/d3-ease/master/img/bounceIn.png" alt="bounceIn" width="100%" height="240" style="max-width:100%;"></a></p>
<p><a name="user-content-easeBounce" href="#easeBounce">#</a> d3.<b>easeBounce</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/bounce.js" title="Source">&lt;&gt;</a>
<br><a name="user-content-easeBounceOut" href="#easeBounceOut">#</a> d3.<b>easeBounceOut</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/bounce.js#L16" title="Source">&lt;&gt;</a></p>
<p>Reverse bounce easing; equivalent to 1 - <a href="#easeBounceIn">bounceIn</a>(1 - <em>t</em>).</p>
<p><a href="http://bl.ocks.org/mbostock/248bac3b8e354a9103c4/#bounceOut" rel="nofollow"><img src="https://raw.githubusercontent.com/d3/d3-ease/master/img/bounceOut.png" alt="bounceOut" width="100%" height="240" style="max-width:100%;"></a></p>
<p><a name="user-content-easeBounceInOut" href="#easeBounceInOut">#</a> d3.<b>easeBounceInOut</b>(<i>t</i>) <a href="https://github.com/d3/d3-ease/blob/master/src/bounce.js#L20" title="Source">&lt;&gt;</a></p>
<p>Symmetric bounce easing; scales <a href="#easeBounceIn">bounceIn</a> for <em>t</em> in [0, 0.5] and <a href="#easeBounceOut">bounceOut</a> for <em>t</em> in [0.5, 1].</p>
<p><a href="http://bl.ocks.org/mbostock/248bac3b8e354a9103c4/#bounceInOut" rel="nofollow"><img src="https://raw.githubusercontent.com/d3/d3-ease/master/img/bounceInOut.png" alt="bounceInOut" width="100%" height="240" style="max-width:100%;"></a></p>
</article>
  </div>

  </div>

  <button type="button" data-facebox="#jump-to-line" data-facebox-class="linejump" data-hotkey="l" class="d-none">Jump to Line</button>
  <div id="jump-to-line" style="display:none">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
      <input class="form-control linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
      <button type="submit" class="btn">Go</button>
</form>  </div>


  </div>
  <div class="modal-backdrop js-touch-events"></div>
</div>

    </div>
  </div>

  </div>

      
<div class="footer container-lg px-3" role="contentinfo">
  <div class="position-relative d-flex flex-justify-between py-6 mt-6 f6 text-gray border-top border-gray-light ">
    <ul class="list-style-none d-flex flex-wrap ">
      <li class="mr-3">&copy; 2018 <span title="0.18915s from unicorn-910688904-30fpt">GitHub</span>, Inc.</li>
        <li class="mr-3"><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li class="mr-3"><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li class="mr-3"><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li class="mr-3"><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>
    </ul>

    <a href="https://github.com" aria-label="Homepage" class="footer-octicon" title="GitHub">
      <svg aria-hidden="true" class="octicon octicon-mark-github" height="24" version="1.1" viewBox="0 0 16 16" width="24"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>
    <ul class="list-style-none d-flex flex-wrap ">
        <li class="mr-3"><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact GitHub</a></li>
      <li class="mr-3"><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li class="mr-3"><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li class="mr-3"><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li class="mr-3"><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>

    </ul>
  </div>
</div>



  <div id="ajax-error-message" class="ajax-error-message flash flash-error">
    <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.865 1.52c-.18-.31-.51-.5-.87-.5s-.69.19-.87.5L.275 13.5c-.18.31-.18.69 0 1 .19.31.52.5.87.5h13.7c.36 0 .69-.19.86-.5.17-.31.18-.69.01-1L8.865 1.52zM8.995 13h-2v-2h2v2zm0-3h-2V6h2v4z"/></svg>
    <button type="button" class="flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
      <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
    </button>
    You can't perform that action at this time.
  </div>


    
    <script crossorigin="anonymous" integrity="sha512-LpTtPGbYVV+NuVcO3FkheTQ7cU72aRS257vu6oyc8h2RmHnXnQFMOnc5nLnahUhr/SAFPHtVfFJ70cQLXAYH1g==" src="https://assets-cdn.github.com/assets/frameworks-2e94ed3c66d8555f8db9570edc592179343b714ef66914b6e7bbeeea8c9cf21d919879d79d014c3a77399cb9da85486bfd20053c7b557c527bd1c40b5c0607d6.js"></script>
    
    <script async="async" crossorigin="anonymous" integrity="sha512-k7KbMMnBd9DvHvAfs4HIAxAgiGtStBNJuecA99e23CeX4QaPj3Z2jxLg8YvU/IxIIUQcPJ3CeSAObKfHkTC47A==" src="https://assets-cdn.github.com/assets/github-93b29b30c9c177d0ef1ef01fb381c8031020886b52b41349b9e700f7d7b6dc2797e1068f8f76768f12e0f18bd4fc8c4821441c3c9dc279200e6ca7c79130b8ec.js"></script>
    
    
    
    
  <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner d-none">
    <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.865 1.52c-.18-.31-.51-.5-.87-.5s-.69.19-.87.5L.275 13.5c-.18.31-.18.69 0 1 .19.31.52.5.87.5h13.7c.36 0 .69-.19.86-.5.17-.31.18-.69.01-1L8.865 1.52zM8.995 13h-2v-2h2v2zm0-3h-2V6h2v4z"/></svg>
    <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
    <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
  </div>
  <div class="facebox" id="facebox" style="display:none;">
  <div class="facebox-popup">
    <div class="facebox-content" role="dialog" aria-labelledby="facebox-header" aria-describedby="facebox-description">
    </div>
    <button type="button" class="facebox-close js-facebox-close" aria-label="Close modal">
      <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
    </button>
  </div>
</div>


  </body>
</html>

