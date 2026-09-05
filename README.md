# Awesome frontend security with stars

<p><img src="/logo.png" alt="awesome-frontend-security" srcset="/logo.png 2x"/></p>

[![Awesome](https://awesome.re/badge-flat2.svg)](https://github.com/sindresorhus/awesome) ⭐ 503,109 | 🐛 106 | 📅 2026-09-02

## Contents

* [Code](#code)
  * [Linters](#linters)
  * [Sanitizers](#sanitizers)
  * [Serializers](#serializers)
* [Dependencies](#dependencies)
* [Headers](#headers)
  * [Content-Security-Policy](#content-security-policy)
  * [X-XSS-Protection](#x-xss-protection)
  * [X-Frame-Options](#x-frame-options)
* [Articles](#articles)
* [Other lists](#other-lists)

## Code

* [AJAX Security Cheatsheet](https://github.com/OWASP/CheatSheetSeries/blob/master/cheatsheets/AJAX_Security_Cheat_Sheet.md) ⭐ 33,082 | 🐛 63 | 🌐 Python | 📅 2026-09-04 - A starting point for AJAX security.
* [JavaScript Secure Coding Practices](https://checkmarx.gitbooks.io/js-scp/content/) - A guide written for anyone who is using the JavaScript for web development.
* [Security Policy](https://help.github.com/en/articles/adding-a-security-policy-to-your-repository) - How to add a security policy to your Github repository.

### Linters

* [`eslint-plugin-security`](https://github.com/nodesecurity/eslint-plugin-security) ⭐ 2,374 | 🐛 22 | 🌐 JavaScript | 📅 2026-09-03 - ESLint rules for Node Security.
* [`eslint-plugin-no-unsanitized`](https://github.com/mozilla/eslint-plugin-no-unsanitized) ⭐ 248 | 🐛 37 | 🌐 JavaScript | 📅 2026-09-03 - ESLint rules to disallows unsafe innerHTML, outerHTML, insertAdjacentHTML and alike.
* [`eslint-config-sec`](https://github.com/rustcohlnikov/eslint-config-sec) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2019-10-15 - ESLint rules for writing safe and secure client code.

### Sanitizers

* [`dompurify`](https://github.com/cure53/DOMPurify) ⭐ 17,357 | 🐛 4 | 🌐 JavaScript | 📅 2026-09-04 - XSS sanitizer for HTML, MathML and SVG
* [`sanitize-html`](https://github.com/apostrophecms/sanitize-html) ⚠️ Archived - Clean up user-submitted HTML.

### Serializers

* [`serialize-javascript`](https://github.com/yahoo/serialize-javascript) ⭐ 2,923 | 🐛 43 | 🌐 JavaScript | 📅 2026-08-29 - Serialize JavaScript safely - HTML characters and JS line terminators are escaped automatically.

## Dependencies

* [Vulnerable Dependency Management](https://github.com/OWASP/CheatSheetSeries/blob/master/cheatsheets/Vulnerable_Dependency_Management_Cheat_Sheet.md#tools) ⭐ 33,082 | 🐛 63 | 🌐 Python | 📅 2026-09-04 - About tools for detecting vulnerable third-party dependencies.
* [`audit-ci`](https://github.com/IBM/audit-ci) ⭐ 297 | 🐛 20 | 🌐 TypeScript | 📅 2025-09-17 - NPM and Yarn dependencies audit for CI/CD.
* [`dtrack-audit`](https://github.com/ozonru/dtrack-audit) - OWASP Dependency Track API client for CI/CD.
* [Github Automated Security Fixes](https://help.github.com/en/articles/configuring-automated-security-fixes) - How to use automated or manual pull requests to easily update vulnerable dependencies.

## Headers

* [Security Headers](https://securityheaders.com/) - Check your website's HTTP response headers for security.

### Content-Security-Policy

#### 📚Learn

* [MDN](https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP) - An article on MDN.
* [CSP Is Dead, Long Live CSP!](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/45542.pdf) - On the Insecurity of Whitelists and the Future of Content Security Policy.
* [Strict CSP](https://csp.withgoogle.com/docs/strict-csp.html) - To get real value out of CSP, your policy must prevent the execution of untrusted scripts.

#### 🧪Create

* [`csp-html-webpack-plugin`](https://github.com/slackhq/csp-html-webpack-plugin) ⭐ 172 | 🐛 28 | 🌐 JavaScript | 📅 2026-06-02 - Generates meta content for your Content Security Policy tag.
* [Webpack CSP configuration](https://webpack.js.org/guides/csp/) - Webpack is capable of adding nonce(number used once) to all scripts that it loads.
* [CSP Hash Generator](https://report-uri.com/home/hash) - Script and style hasher for `script-src` and `style-src` directives to disallow inline scripts and styles. More [here](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Security-Policy/script-src#Unsafe_inline_script).

#### 🔍Validate

* [CSP Tester](https://github.com/yandex/csp-tester) ⭐ 56 | 🐛 3 | 🌐 JavaScript | 📅 2018-09-02 - Browser extension for testing Content Security Policy (CSP).
* [CSP Evaluator](https://csp-evaluator.withgoogle.com/) - Paste your policy and check if its safe and strong enough.
* [CSP Header Inspector](https://cspvalidator.org) - Validate your policies as served from the given URL.

#### 🤔Analyse

* [CSP WTF?](https://github.com/nico3333fr/CSP-useful/blob/master/csp-wtf/explained.md) ⭐ 502 | 🐛 8 | 🌐 PHP | 📅 2026-07-10 - Explanations for strange CSP Report notifications.

### X-XSS-Protection

#### 📚Learn

* [MDN](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-XSS-Protection) - An article on MDN.

### X-Frame-Options

#### 📚Learn

* [MDN](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options) - An article on MDN.

## Articles

* [Trusted Types help prevent Cross-Site Scripting](https://developers.google.com/web/updates/2019/02/trusted-types) - About new browser API that might help obliterate DOM XSS.
* [Cybersecurity threatscape](https://www.ptsecurity.com/ww-en/analytics/cybersecurity-threatscape-2019-q2/) - Positive Technologies' quarter report on cyber threats and recommendations on how to stay safe.
* [The Most Common XSS Vulnerability in React.js Applications](https://medium.com/node-security/the-most-common-xss-vulnerability-in-react-js-applications-2bdffbcc1fa0)

## Other lists

* [Awesome Web Security](https://github.com/qazbnm456/awesome-web-security) ⭐ 13,770 | 🐛 2 | 🌐 Python | 📅 2026-09-05 - A curated list of Web Security materials and resources.
* [CSP useful](https://github.com/nico3333fr/CSP-useful) ⭐ 502 | 🐛 8 | 🌐 PHP | 📅 2026-07-10 - A collection of parsers, examples and tips for Content Security Policy.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-05._
