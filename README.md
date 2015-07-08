# Public-Config 

> The config files for all applications & libraries

All config files must named in forms below:

> `read` {APPLICATION_KEY}\_{SCOPE}_{ENVIRONMENT}.ini

> `segment` {APPLICATION_KEY}\_{SCOPE}_{ENVIRONMENT}.ini.segment

`.segment` file will merged by {config}_base.ini.

It will load {config}\_base.ini while {config}_{environment}.ini not exist.