- Today I learned that ES6 standard `fetch()` does not expose `Set-Cookie` header
    in `headers` attribute for security issue. This can be bypassed with
    `superagent` or other legacy library if necessary (for example, in electron
    or other browser based engines).
