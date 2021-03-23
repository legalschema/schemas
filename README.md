<p align="center">
  <a href="https://www.legalschema.org/">
    <img src="assets/images/logo.png" alt="UK Legal Schemas Logo" width="400" />
  </a>
</p>  

<h1 align="center">UK Legal Schemasy</h1>

This repository hosts all UK Legal Schemas. Models are captured using the [Concerto][concerto] modeling language; a platform and runtime neutral typed schema language.

The build system for this repository publishes the models to: https://schemas.legalschema.org

Environment Variables used by the build system:

- SERVER_ROOT : the root URL for the server. Used when generating absolute hyperlinks.
- FORCE_PUBLISH : disabled the download of external models and model validation. Should be used with care!
