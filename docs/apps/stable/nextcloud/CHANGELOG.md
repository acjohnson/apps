# Changelog<br>


<a name="nextcloud-4.0.3"></a>
### [nextcloud-4.0.3](https://github.com/truecharts/apps/compare/nextcloud-4.0.2...nextcloud-4.0.3) (2021-09-10)

#### Fix

* repair wrong initcontainer format on nextcloud



<a name="nextcloud-4.0.2"></a>
### [nextcloud-4.0.2](https://github.com/truecharts/apps/compare/nextcloud-4.0.1...nextcloud-4.0.2) (2021-09-10)

#### Fix

* update common to ensure initcontainer can always be run as root



<a name="nextcloud-4.0.1"></a>
### [nextcloud-4.0.1](https://github.com/truecharts/apps/compare/nextcloud-4.0.0...nextcloud-4.0.1) (2021-09-10)

#### Fix

* move runAsNonRoot to container securityContext to allow root sidecarts ([#954](https://github.com/truecharts/apps/issues/954))



<a name="nextcloud-4.0.0"></a>
### [nextcloud-4.0.0](https://github.com/truecharts/apps/compare/nextcloud-3.7.16...nextcloud-4.0.0) (2021-09-09)

#### Chore

* update Apps containing initcontainers  -not breaking on SCALE- ([#952](https://github.com/truecharts/apps/issues/952))

#### Feat

* Add regex validation to resources CPU and RAM for all apps ([#935](https://github.com/truecharts/apps/issues/935))



<a name="nextcloud-3.7.16"></a>
### [nextcloud-3.7.16](https://github.com/truecharts/apps/compare/nextcloud-3.7.15...nextcloud-3.7.16) (2021-09-08)

#### Revert

* undo fix tryout for TRUSTED_PROXIES



<a name="nextcloud-3.7.15"></a>
### [nextcloud-3.7.15](https://github.com/truecharts/apps/compare/nextcloud-3.7.14...nextcloud-3.7.15) (2021-09-08)

#### Feat

* Add IPWhitelist, redirectRegex and (internal) nextcloud middlewares ([#929](https://github.com/truecharts/apps/issues/929))
* Pre-commit and tag-appversion syncing ([#926](https://github.com/truecharts/apps/issues/926))

#### Fix

* Add initcontainer to force refresh TRUSTED_DOMAINS ([#930](https://github.com/truecharts/apps/issues/930))

<a name="nextcloud-3.7.14"></a>
## [nextcloud-3.7.14](https://github.com/truecharts/apps/compare/nextcloud-3.7.13...nextcloud-3.7.14) (2021-09-08)