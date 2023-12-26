- 👋 Hi, I’m @_@
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
KOMUORAS/KOMUORAS is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<html lang="ru" xmlns="http://www.w3.org/1999/xhtml" style="position: fixed; overflow: hidden;" ng-controller="
<!--
 HAS_SBMS_INT version 2.9.4-rc.
 All rights reserved. You are not allowed to copy or modify this code. Commercial use requires license.
 Copyright (c) 2006-2021 "Nexign" JSC (St.Petersburg, Russia; www.nexign.com)
-->
<!DOCTYPE html>
<html lang="ru" xmlns="http://www.w3.org/1999/xhtml" style="position: fixed; overflow: hidden;"
      ng-controller="AppController as app">
<head>
  <meta charset="utf-8"/>
  <meta http-equiv="X-UA-Compatible" content="IE=EDGE"/>
  <title id="SHELL-TITLE">SBMS</title>

  <link rel="stylesheet" href="/ps/theme/shell/shell.css" type="text/css"/>
  <link rel="stylesheet" href="/ps/theme/shell/styles.css" type="text/css"/>

  <script src="/ps/sbms/ps.js"></script>
  <script src="/ps/ng-core/require.js"></script>
  <script src="/ps/ng-core/core-all.js"></script>
  <script src="/ps/ng-components/components-all.js"></script>
  <script src="/ps/sbms/define.js"></script>
</head>
<body class="sbms-shell"
      tabindex="0"
      id="PS_SBMS_WORK_WINDOW"
      style="overflow: hidden;">
<!--TODO переименовать-->
<div id="LOGOTYPE_TAB" class="layout">
  <div id="SHELL_TOPBAR" class="topbar">
    <h1 id="SHELL_HEADING" class="system-name"></h1>
    <div id="SHELL_MENU_OVER_HORIZONTAL" class="menu-container"></div>
    <div id="SHELL_MENU_SCROLL_BUTTONS" class="menu_scroll_buttons">
      <ps-icon icon="arr-left" class="menu_scroll_left"></ps-icon>
      <ps-icon icon="arr-right" class="menu_scroll_right"></ps-icon>
    </div>
    <div id="SHELL_USER_MENU" class="user-menu">
      <div class="topbar-user-time-container">
      </div>
      <div class="topbar-settings">
      </div>
      <a class="topbar-exit" id="SHELL_CLOSE1">
      </a>
    </div>
  </div>
  <div id="SHELL_WORKSPACE_AREA" class="workspace">
        <ps-splitter options="{orientation: 'vertical'}" id="SHELL_SPLITTER">
          <ps-splitter-zone id="SHELL_SPLITTER_ZONE_FIRST" class="ng-hide" min-size="'150px'" style="max-width: 25%;">
            <div id="SHELL_MENU_OVER_VERTICAL" class="menu-container-vertical" style="width: 100%;"></div>
          </ps-splitter-zone>
          <ps-splitter-zone id="SHELL_SPLITTER_ZONE_SECOND">
            <div id="SHELL_CONTENT" class="content content_flex" style="width: 100%; height: 100%;">
              <div id="CAPTION" class="sbms-caption sbms-caption_flex"  style="display: none;">
                <div id="SHELL_CAPTION" class="sbms-caption__shell-caption">
                  <ps-breadcrumbs breadcrumbs="app.breadcrumbs"></ps-breadcrumbs>
                  <div id="SHELL_BREADCRUMB" class="caption-breadcrumb"></div>
                  <span id="SHELL_REDIRECT" class="external-bis" onclick="HSIRedirect();"
                        style="display:none;">
                                        <span class="external-bis__separator"></span>
                                        <a title="Перейти в GF" class="external-bis__link">
                                            <label class="external-bis__link__label">Перейти в GF</label>
                                        </a>
                                    </span>
                </div>
                <div class="shell-caption-navigation" style="display:none;" id="listNavigation">

                  <a class="shell-caption-navigation__item shell-caption-navigation__item_first"
                     id="listNavigationFirstButton"></a>
                  <span class="shell-caption-navigation__separator"></span>
                  <a class="shell-caption-navigation__item shell-caption-navigation__item_prev"
                     id="listNavigationPreviousButton">
                    <label class="shell-caption-navigation__label"
                           id="listNavigationPreviousLabel"></label>
                  </a>
                  <span class="shell-caption-navigation__separator"></span>
                  <a class="shell-caption-navigation__item shell-caption-navigation__item_next"
                     id="listNavigationNextButton">
                    <label class="shell-caption-navigation__label"
                           id="listNavigationNextLabel"></label>
                  </a>
                  <span class="shell-caption-navigation__separator"></span>
                  <a class="shell-caption-navigation__item shell-caption-navigation__item_last"
                     id="listNavigationLastButton"></a>
                </div>
                <div id="SHELL_FORM_HEAD" class="title-area-info">
                  <div id="FORM_TUNING" class="info-settings"><a class="title-area-link"
                                                                 id="FORM_TUNING1"
                                                                 onclick="shell()._call_tuning_func()">Настройки</a>
                  </div>
                  <div class="info-refresh" style="display:none;" id="refreshElement"><a
                          class="title-area-link"
                          id="refreshElementButton">Обновить</a>
                  </div>
                </div>

              </div>
              <ps-splitter options="{orientation: 'vertical'}" id="ADDITIONAL_INFO_ZONE_SPLITTER">
                <ps-splitter-zone id="ADDITIONAL_INFO_ZONE_SPLITTER_ZONE_FIRST" style="display: flex; flex-direction: column">
                  <div id="SSW_WORKFRAMES_CONTAINER" class="workframe-shell" style="width: 100%; height: 100%;"></div>
                </ps-splitter-zone>
                <ps-splitter-zone id="ADDITIONAL_INFO_ZONE_SPLITTER_ZONE_SECOND" min-size="'150px'" style="max-width: 25%;overflow-y: auto;" class="ng-hide">
                  <div id="ADDITIONAL_INFO_ZONE" ></div>
                </ps-splitter-zone>
            </div>

          </ps-splitter-zone>
  </div>
</div>
<span id="sbms-foo"></span>
</body>
</html>

