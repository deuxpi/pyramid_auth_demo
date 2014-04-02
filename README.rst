This repository contains a clone of Michael Merickel's tutorial on Pyramid
authentication and authorization demo which uses pyramid_contextauth to
provide different authentication policies for different resources. In this
example, the user pages are protected by Basic HTTP authentication instead of
redirecting to the login page. This simulates different authentication schemes
that could be used for either basic usage of the site or for providing an
administrative interface or API.

The original documentation is available at
http://michael.merickel.org/projects/pyramid_auth_demo.

The pyramid_contextauth extension provides the services to register multiple
authentication policies. The code is available on GitHub at
https://github.com/hadrien/pyramid_contextauth
