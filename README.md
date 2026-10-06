# AL-Go Template

## This fork and its sample

Fork of [AL-Go-Workshop/MyApp](https://github.com/AL-Go-Workshop/MyApp); retain the original AL-Go template and Freddy Kristiansen publisher attribution. This checkout contains three projects: [W1](W1/MyApp.W1/app.json), [DK](DK/MyApp.DK/app.json) and [ES](ES/MyApp.ES/app.json), with application **25.0.0.0**, runtime **14.0** and separate ID ranges.

The `.al` files extend **Customer List**, but their Hello World messages are commented out. The expected current behavior is therefore no additional popup when opening Customers. This is a localization/dependency example, not a complete business application.

Clone `https://github.com/javiarmesto/MyApp.git` and open `al.code-workspace`. Select W1 or a country project, configure your sandbox and download symbols. W1 depends on **Common** and **Licensing** from Freddy Kristiansen; DK/ES also depend on W1. Those dependency sources are not included in this checkout, so obtain the matching packages from the original workshop before compiling. Do not assume that a fresh clone builds by itself.

Compile and publish dependencies before country apps in a compatible sandbox, following the upstream AL-Go guide below. `.github/` contains AL-Go automation; DK/ES/W1 contain the examples. Static inspection: **6 October 2026**; no AL build or workflow execution performed. No applicable license file was confirmed for this fork. [Compare fork and parent](https://github.com/AL-Go-Workshop/MyApp/compare/main...javiarmesto:MyApp:main).

## Per Tenant Extension Project
This template repository can be used for managing Per Tenant Extensions for Business Central.

Please consult https://github.com/microsoft/AL-Go/#readme for scenarios on usage
