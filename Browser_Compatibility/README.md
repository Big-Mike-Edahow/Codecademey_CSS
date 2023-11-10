BROWSER COMPATIBILITY

We can check whether a CSS feature is available on specific browsers using tools like caniuse.com.

Browsers have default styles which we can check using resources like browserdefaultstyles.com.

We sometimes need to use browser-specific prefixes, especially for new CSS features.

Polyfills provide a way to support newer web features on older browsers.

Understand how CSS feature queries work and when to use them.

Understand the syntax of using the @supports at-rule and using logical operators such as not, and, and or. @supports (aspect-ratio : 4/3) {
  // Any code here will run if the aspect-ratio property is supported
}

Understand the differences in the two approaches of addressing browser compatibility: graceful degradation and progressive enhancement.

Use CSS feature queries for the progressive enhancement approach.

CSS feature queries allow you to address browser compatibility issues by checking whether the browser supports a CSS feature or not.

It is a valuable tool in the web developer’s toolbox to deliver a uniform user experience across various browsers.
