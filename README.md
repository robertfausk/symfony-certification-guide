Symfony certification guide
===========================

This is not an official guide, it's only a compilation of links extracted from the documentation based on the [Symfony Certification](https://sensiolabs.com/en/symfony/certification.html) page topics.

Even if you have no plans to take the Symfony certification exam, this list of resources may help you better understand the Symfony framework.

Feel free to fork and send a PR.

### **Topics**
---
#### **PHP and Web Security**
* Object Oriented Programming  
http://www.php.net/manual/en/oop5.intro.php
* Namespaces  
http://www.php.net/manual/en/language.namespaces.php  
https://knpuniversity.com/screencast/php-namespaces-in-120-seconds/namespaces  
* Interfaces  
http://www.php.net/manual/en/language.oop5.interfaces.php
* Anonymous functions and closures  
http://www.php.net/manual/en/functions.anonymous.php
* Abstract classes  
http://www.php.net/manual/en/language.oop5.abstract.php
* Exception and error handling  
http://php.net/manual/en/language.exceptions.php  
http://php.net/manual/en/language.errors.basics.php
* Traits  
http://php.net/manual/en/language.oop5.traits.php
* PHP extensions  
http://php.net/manual/en/extensions.php
* SPL  
http://php.net/manual/en/book.spl.php
* Web security (XSS, CSRF, etc.)  
http://php.net/manual/en/security.php  
https://www.owasp.org/index.php/PHP_Security_Cheat_Sheet

---

#### **HTTP**
* Client / Server interaction  
http://symfony.com/doc/3.0/book/http_fundamentals.html
* HTTP request  
https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol#Request_message  
http://symfony.com/doc/3.0/components/http_foundation/introduction.html#request
* HTTP response  
https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol#Response_message  
http://symfony.com/doc/3.0/components/http_foundation/introduction.html#response
* Status codes  
http://en.wikipedia.org/wiki/List_of_HTTP_status_codes  
https://tools.ietf.org/html/rfc2616#section-10
* HTTP methods  
https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol#Request_methods  
http://www.restapitutorial.com/lessons/httpmethods.html
* Cookies  
https://en.wikipedia.org/wiki/HTTP_cookie
* Caching  
https://tools.ietf.org/html/rfc2616#section-13
* Content negotiation  
https://en.wikipedia.org/wiki/Content_negotiation  
https://developer.mozilla.org/en-US/docs/Web/HTTP/Content_negotiation  
https://www.w3.org/Protocols/rfc2616/rfc2616-sec12.html
* Language detection  
https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Accept-Language

---

#### **Symfony Architecture**
* Standard edition of Symfony2  
http://symfony.com/distributions
* Components  
http://symfony.com/doc/3.0/components/index.html
* Bundles  
http://symfony.com/doc/3.0/cookbook/bundles/best_practices.html  
http://symfony.com/doc/3.0/quick_tour/the_architecture.html#understanding-the-bundle-system
* Bridges  
http://stackoverflow.com/questions/11888522/what-are-symfony-bridges-bundles-and-vendor?answertab=votes#tab-top  
http://symfony.com/doc/3.0/request/psr7.html  
http://symfony.com/doc/3.0/components/phpunit_bridge.html
*  Configuration  
http://symfony.com/doc/3.0/cookbook/configuration/index.html  
http://symfony.com/doc/3.0/components/config/index.html  
http://symfony.com/doc/3.0/cookbook/bundles/best_practices.html#configuration  
http://symfony.com/doc/3.0/cookbook/bundles/extension.html  
*  Code organization  
http://symfony.com/doc/3.0/quick_tour/the_architecture.html#understanding-the-directory-structure
* Request handling  
http://symfony.com/doc/3.0/book/http_fundamentals.html#the-journey-from-the-request-to-the-response  
http://symfony.com/doc/3.0/introduction/http_fundamentals.html
* Exception handling  
http://symfony.com/doc/3.0/controller/error_pages.html
* Event dispatcher and kernel events  
http://symfony.com/doc/3.0/event_dispatcher.html  
http://symfony.com/doc/3.0/reference/events.html  
http://symfony.com/doc/3.0/create_framework/event_dispatcher.html  
http://symfony.com/doc/3.0/components/event_dispatcher.html
* Official best practices  
http://symfony.com/doc/3.0/best_practices/index.html
* Release management  
https://symfony.com/doc/3.0/contributing/community/releases.html
* Backward compatibility promise  
http://symfony.com/doc/3.0/contributing/code/bc.html
* Deprecations best practices  
http://symfony.com/doc/3.0/contributing/code/conventions.html#deprecations  
http://symfony.com/blog/paving-the-way-for-symfony-3-with-the-deprecation-detector-tool

---

#### **Standardization**
* Release management and roadmap schedule  
https://symfony.com/doc/3.0/contributing/community/releases.html
* Framework interoperability and PSRs  
* Naming conventions  
http://symfony.com/doc/3.0/contributing/code/standards.html#naming-conventions
* Coding standards  
http://symfony.com/doc/3.0/contributing/code/standards.html
* Third-party libraries integration   
http://symfony.com/doc/3.0/cookbook/bundles/installation.html
* Composer packages handling  
http://symfony.com/doc/3.0/book/installation.html  
https://knpuniversity.com/screencast/composer
* Development best practices
http://symfony.com/doc/3.0/best_practices/index.html
* Framework overloading   
http://symfony.com/doc/3.0/cookbook/bundles/override.html
* Semantic versioning  
http://semver.org/

---

#### **Bundles**
* Naming conventions  
http://symfony.com/doc/3.0/cookbook/bundles/best_practices.html#bundle-name
* Code organization  
http://symfony.com/doc/3.0/cookbook/bundles/best_practices.html#directory-structure
* The controllers  
http://symfony.com/doc/3.0/cookbook/bundles/best_practices.html#controllers  
http://symfony.com/doc/3.0/cookbook/controller/index.html  
http://symfony.com/doc/3.0/book/controller.html
* The views  
http://symfony.com/doc/3.0/quick_tour/the_view.html
* The resources  
* Overriding default error pages  
http://symfony.com/doc/3.0/bundles/inheritance.html#overriding-resources-templates-routing-etc
* Bundle inheritance  
http://symfony.com/doc/3.0/bundles/inheritance.html
* Event dispatcher and kernel events  
* Semantic configuration and compiler passes  
http://symfony.com/doc/3.0/bundles/configuration.html  
http://symfony.com/doc/3.0/bundles/extension.html

---

#### **Controllers**
* Naming conventions  
http://symfony.com/doc/3.0/book/routing.html#controller-string-syntax
* The base Controller class  
http://symfony.com/doc/3.0/controller.html#the-base-controller-class-services
* The request  
http://symfony.com/doc/3.0/book/controller.html#requests-controller-response-lifecycle  
http://symfony.com/doc/3.0/components/http_foundation/introduction.html#request
* The response  
http://symfony.com/doc/3.0/book/controller.html#requests-controller-response-lifecycle  
http://symfony.com/doc/3.0/components/http_foundation/introduction.html#response
* The cookies  
http://symfony.com/doc/3.0/components/http_foundation/introduction.html#setting-cookies
* The session  
http://symfony.com/doc/3.0/book/controller.html#managing-the-session  
http://symfony.com/doc/3.0/components/http_foundation/sessions.html
* The flash messages  
http://symfony.com/doc/3.0/book/controller.html#flash-messages  
http://symfony.com/doc/3.0/components/http_foundation/sessions.html#flash-messages
* Redirects  
http://symfony.com/doc/3.0/book/controller.html#redirecting  
http://symfony.com/doc/3.0/routing/redirect_in_config.html  
http://symfony.com/doc/3.0/routing/redirect_trailing_slash.html
* Internal redirects  
http://symfony.com/doc/3.0/controller/forwarding.html  
http://symfony.com/doc/3.0/book/controller.html#forwarding-to-another-controller
* Generate 404 pages  
http://symfony.com/doc/3.0/book/controller.html#managing-errors-and-404-pages  
http://symfony.com/doc/3.0/cookbook/controller/error_pages.html#customizing-the-404-page-and-other-error-pages
* File upload  
http://symfony.com/doc/3.0/controller/upload_file.html
* Built-in internal controllers  
http://symfony.com/doc/3.0/templating/render_without_controller.html

---

#### **Routing**
http://symfony.com/doc/3.0/components/routing.html
* Configuration (YAML / XML / PHP & annotations)  
http://symfony.com/doc/3.0/book/routing.html#basic-route-configuration
* Restrict URL parameters  
http://symfony.com/doc/3.0/book/routing.html#routing-with-placeholders
* Set default values to URL parameters  
http://symfony.com/doc/3.0/book/routing.html#required-and-optional-placeholders
* Generate URL parameters  
http://symfony.com/doc/3.0/book/routing.html#generating-urls  
http://symfony.com/doc/3.0/book/routing.html#generating-urls-with-query-strings
* Trigger redirects  
http://symfony.com/doc/master/cmf/components/routing/dynamic.html#redirections  
http://symfony.com/doc/3.0/cookbook/routing/redirect_in_config.html
* Special internal routing attributes  
https://symfony.com/doc/3.0/routing/extra_information.html  
https://symfony.com/doc/3.0/routing/external_resources.html
* Domain name matching  
https://symfony.com/doc/3.0/routing/hostname_pattern.html
* Conditional request matching  
https://symfony.com/doc/3.0/routing/conditions.html
* HTTP methods matching  
http://symfony.com/doc/3.0/routing/requirements.html#adding-http-method-requirements
* User's locale guessing  
http://symfony.com/doc/3.0/translation/locale.html#the-locale-and-the-url
* Router debugging  
http://symfony.com/doc/3.0/routing/debug.html  
https://symfony.com/doc/3.0/routing.html#troubleshooting

---

#### **Templating with Twig**
* Auto escape  
http://twig.sensiolabs.org/doc/tags/autoescape.html  
http://symfony.com/doc/3.0/book/templating.html#output-escaping-in-twig
* Template inheritance  
http://twig.sensiolabs.org/doc/tags/extends.html  
http://twig.sensiolabs.org/doc/templates.html#template-inheritance  
http://symfony.com/doc/3.0/book/templating.html#template-inheritance-and-layouts
* Global variables  
http://symfony.com/doc/3.0/templating/global_variables.html  
http://symfony.com/doc/3.0/templating/app_variable.html
* Filters and functions  
http://twig.sensiolabs.org/doc/functions/index.html  
http://twig.sensiolabs.org/doc/filters/index.html
* Template includes  
http://twig.sensiolabs.org/doc/tags/include.html
* loops and conditions  
http://twig.sensiolabs.org/doc/tags/for.html  
http://twig.sensiolabs.org/doc/templates.html#control-structure  
https://twig.sensiolabs.org/doc/2.x/tags/if.html
* Urls generation  
http://symfony.com/doc/3.0/book/routing.html#generating-urls-from-a-template  
http://symfony.com/doc/3.0/book/templating.html#linking-to-pages
* Controller rendering  
http://symfony.com/doc/3.0/controller.html#rendering-templates
* Call a controller from a view  
https://symfony.com/doc/3.0/templating/embedding_controllers.html
* Translations and pluralization  
http://symfony.com/doc/3.0/translation.html#translations-in-templates
* String interpolation  
https://twig.sensiolabs.org/doc/2.x/templates.html#string-interpolation
* Assets management  
https://symfony.com/doc/3.0/assetic/asset_management.html  
http://symfony.com/doc/current/templating.html#linking-to-assets
* Debugging variables  
http://symfony.com/doc/current/templating/debug.html

---

#### **Forms**
* Forms creation  
http://symfony.com/doc/3.0/forms.html#creating-a-simple-form
* Forms handling  
http://symfony.com/doc/3.0/forms.html#handling-form-submissions
* Form types  
http://symfony.com/doc/3.0/forms.html#creating-form-classes  
http://symfony.com/doc/3.0/forms.html#built-in-field-types  
http://symfony.com/doc/3.0/form/create_custom_field_type.html
* Forms rendering with Twig  
http://symfony.com/doc/3.0/forms.html#rendering-the-form  
http://symfony.com/doc/3.0/form/form_customization.html  
http://symfony.com/doc/3.0/form/rendering.html
* Forms theming  
http://symfony.com/doc/3.0/form/form_themes.html  
http://symfony.com/doc/3.0/form/form_customization.html#what-are-form-themes
* CSRF protection  
http://symfony.com/doc/3.0/form/csrf_protection.html
* Handling file upload  
http://symfony.com/doc/3.0/controller/upload_file.html  
http://symfony.com/doc/3.0/reference/forms/types/file.html
* Built-in form types  
http://symfony.com/doc/3.0/reference/forms/types.html
* Data transformers  
http://symfony.com/doc/3.0/form/data_transformers.html
* Form events  
http://symfony.com/doc/3.0/form/events.html  
http://symfony.com/doc/3.0/form/dynamic_form_modification.html
* Form type extensions  
http://symfony.com/doc/3.0/form/create_form_type_extension.html

---

#### **Data Validation**
* PHP object validation  
http://symfony.com/doc/3.0/validation.html#the-basics-of-validation
* Built-in validation constraints  
http://symfony.com/doc/3.0/validation.html#constraints  
http://symfony.com/doc/3.0/reference/constraints.html
* Validation scopes  
http://symfony.com/doc/3.0/validation/custom_constraint.html
* Validation groups  
http://symfony.com/doc/3.0/validation/group_service_resolver.html  
http://symfony.com/doc/3.0/validation/sequence_provider.html
* Group sequence  
http://symfony.com/doc/3.0/validation/sequence_provider.html
* Custom callback validators  
http://symfony.com/doc/3.0/reference/constraints/Callback.html
* Violations builder  
http://symfony.com/doc/3.0/validation/custom_constraint.html

---

#### **Dependency Injection**
* Service container  
http://symfony.com/doc/3.0/service_container.html
* Built-in services  
http://symfony.com/doc/3.0/controller/service.html
* Configuration parameters  
http://symfony.com/doc/3.0/service_container/parameters.html  
http://symfony.com/doc/3.0/service_container/shared.html
* Services registration  
http://symfony.com/doc/3.0/service_container.html#creating-configuring-services-in-the-container
* Tags  
http://symfony.com/doc/3.0/service_container/tags.html  
http://symfony.com/doc/3.0/reference/dic_tags.html
* Semantic configuration  
http://symfony.com/doc/3.0/service_container/alias_private.html
* Factories  
http://symfony.com/doc/3.0/service_container/factories.html
* Compiler passes  
http://symfony.com/doc/3.0/service_container/compiler_passes.html
* Services autowiring  
https://symfony.com/doc/2.8/service_container/autowiring.html  
https://symfony.com/doc/3.0/components/dependency_injection/autowiring.html  
https://knpuniversity.com/screencast/new-in-symfony3/autowiring

---

#### **Security**
* Authentication  
http://symfony.com/doc/3.0/components/security/authentication.html  
http://symfony.com/doc/3.0/security.html#initial-security-yml-setup-authentication  
http://symfony.com/doc/3.0/security.html#authentication-identifying-logging-in-the-user
* Authorization  
http://symfony.com/doc/3.0/components/security/authorization.html  
http://symfony.com/doc/3.0/security.html#denying-access-roles-and-other-authorization  
http://symfony.com/doc/3.0/security.html#authorization-denying-access
* Configuration  
http://symfony.com/doc/3.0/reference/configuration/security.html
* Providers  
http://symfony.com/doc/3.0/security.html#security-user-providers  
http://symfony.com/doc/3.0/security/custom_provider.html  
http://symfony.com/doc/3.0/security/entity_provider.html  
http://symfony.com/doc/3.0/security/custom_authentication_provider.html  
http://symfony.com/doc/3.0/security/multiple_user_providers.html
* Firewalls  
http://symfony.com/doc/3.0/security.html#a-configuring-how-your-users-will-authenticate  
http://symfony.com/doc/3.0/security/pre_authenticated.html  
http://symfony.com/doc/3.0/security/firewall_restriction.html  
http://symfony.com/doc/3.0/components/security/firewall.html
* Users  
http://symfony.com/doc/3.0/security.html#b-configuring-how-users-are-loaded  
http://symfony.com/doc/3.0/security/api_key_authentication.html  
http://symfony.com/doc/3.0/security/entity_provider.html  
http://symfony.com/doc/3.0/security/custom_provider.html
* Passwords encoders  
http://symfony.com/doc/3.0/security.html#c-encoding-the-user-s-password  
http://symfony.com/doc/3.0/security/password_encoding.html  
http://symfony.com/doc/3.0/security/named_encoders.html
* Roles  
http://symfony.com/doc/3.0/security.html#roles  
http://symfony.com/doc/3.0/security.html#hierarchical-roles  
http://symfony.com/doc/3.0/components/security/authorization.html#roles
* Access Control Rules  
http://symfony.com/doc/3.0/security.html#access-control-in-templates  
http://symfony.com/doc/3.0/security.html#access-control-lists-acls-securing-individual-database-objects  
http://symfony.com/doc/3.0/expressions.html#expressions-security  
http://symfony.com/doc/3.0/security/acl.html
* Guard authenticators  
http://symfony.com/doc/3.0/security/guard_authentication.html  
http://symfony.com/blog/new-in-symfony-2-8-guard-authentication-component  
http://symfony.com/doc/3.0/security/multiple_guard_authenticators.html
* Voters and voting strategies  
http://symfony.com/doc/3.0/security/voters.html  
http://symfony.com/doc/3.0/components/security/authorization.html#voters

---

#### **HTTP Cache**
* Cache types (browser, proxies and reverse-proxies)  
http://symfony.com/doc/3.0/http_cache.html
* Expiration (Expires, Cache-Control)  
http://symfony.com/doc/3.0/http_cache.html#expiration-caching
* Validation (ETag, Last-Modified)  
http://symfony.com/doc/3.0/http_cache/validation.html  
http://symfony.com/doc/3.0/http_cache.html#validation-caching
* Client side caching  
* Server side caching  
* Edge Side Includes  
http://symfony.com/doc/3.0/http_cache/esi.html  
http://symfony.com/doc/3.0/http_cache.html#using-edge-side-includes  
http://symfony.com/doc/3.0/http_cache/varnish.html

---

#### **Console**
* Built-in commands  
https://symfony.com/doc/3.0/components/console/usage.html#built-in-commands
* Custom commands  
http://symfony.com/doc/3.0/console.html  
http://symfony.com/doc/3.0/components/console/changing_default_command.html
* Configuration  
http://symfony.com/doc/3.0/console/commands_as_services.html
* Options and arguments  
http://symfony.com/doc/3.0/console/input.html  
http://symfony.com/doc/3.0/components/console/console_arguments.html
* Input and Output objects  
http://symfony.com/doc/3.0/console/command_in_controller.html  
http://symfony.com/doc/3.0/console/coloring.html
* Built-in helpers  
http://symfony.com/doc/3.0/components/console/helpers/index.html  
http://symfony.com/doc/3.0/components/console/helpers/questionhelper.html  
http://symfony.com/doc/3.0/components/console/helpers/formatterhelper.html  
http://symfony.com/doc/3.0/components/console/helpers/progressbar.html  
http://symfony.com/doc/3.0/components/console/helpers/table.html
* Console events  
http://symfony.com/doc/3.0/components/console/events.html
* Verbosity levels  
http://symfony.com/doc/3.0/console/verbosity.html  
http://symfony.com/doc/3.0/logging/monolog_console.html

---

#### **Automated Tests**
* Unit tests with PHPUnit  
http://symfony.com/doc/3.0/testing.html#unit-tests  
http://symfony.com/doc/3.0/best_practices/tests.html
* Functional tests with PHPUnit  
http://symfony.com/doc/3.0/testing.html#functional-tests
* Client object  
http://symfony.com/doc/3.0/testing.html#working-with-the-test-client
* Crawler object  
http://symfony.com/doc/3.0/testing.html#the-crawler
* Profile object  
http://symfony.com/doc/3.0/testing.html#accessing-the-profiler-data  
http://symfony.com/doc/3.0/testing/profiling.html  
http://symfony.com/doc/3.0/profiler.html
* Framework access objects  
http://symfony.com/doc/3.0/book/testing.html#accessing-internal-objects  
http://symfony.com/doc/3.0/book/testing.html#accessing-the-container
* Client configuration  
http://symfony.com/doc/3.0/testing.html#testing-configuration  
http://symfony.com/doc/3.0/testing/http_authentication.html  
http://symfony.com/doc/3.0/testing/doctrine.html
* Request and response objects introspection  
http://symfony.com/doc/3.0/testing.html#accessing-internal-objects
* PHPUnit bridge  
http://symfony.com/doc/3.0/components/phpunit_bridge.html  
http://symfony.com/blog/new-in-symfony-2-7-phpunit-bridge
* Handling legacy deprecated code  
http://symfony.com/doc/3.0/components/phpunit_bridge.html#trigger-deprecation-notices  
http://symfony.com/doc/current/components/phpunit_bridge.html#mark-tests-as-legacy


---

#### **Miscellaneous**
* Error handling  
http://symfony.com/doc/3.0/cookbook/controller/error_pages.html
* Debug the code  
http://symfony.com/doc/3.0/cookbook/debugging.html

### **Resources**
---
#### **Documentation**
* The Symfony Book  
http://symfony.com/doc/3.0/book/index.html
* The Symfony Cookbook  
http://symfony.com/doc/3.0/cookbook/index.html
* The Symfony Book Spanish  
http://librosweb.es/symfony_2_3/  
The Symfony Glossary  
http://symfony.com/doc/3.0/glossary.html

---

#### **Books**
* Desarrollo web ágil con Symfony2 Spanish  
http://symfony.es/libro/  
* A year with Symfony  
https://leanpub.com/a-year-with-symfony  
* Un año con Symfony Spanish  
https://leanpub.com/un-ano-con-symfony  
* Extending Symfony2 Web Application Framework  
http://www.packtpub.com/extending-symfony-2-web-application-framework/book  
* Testing para Aplicaciones Symfony2 Spanish  
https://leanpub.com/testingsymfony2  
* Symfony Enterprise Applications
https://leanpub.com/symfony-enterprise-applications
* Extending Symfony2 Web Application Framework
https://www.packtpub.com/web-development/extending-symfony2-web-application-framework
* Symfony Certification. Unofficial self-study guide  
https://leanpub.com/symfony-selfstudy

---

#### **Other**
* KNP University - PHP and Symfony Tutorial Screencasts  
http://knpuniversity.com/
* SymfonyBricks  
https://symfonybricks.com/
* Symfony2 cheat sheet  
http://www.symfony2cheatsheet.com/
* Symfony2 Tutorials  
http://www.screenfony.com/
* Symfony2 deployment checklist  
http://www.symfony2-checklist.com/
* A Symfony Console CLI tool to train on Symfony certification  
https://github.com/certificationy/certificationy-cli  
* A Symfony Web Platform tool to train on Symfony certification  
http://www.certificationy.com/
