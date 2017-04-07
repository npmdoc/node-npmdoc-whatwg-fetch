# api documentation for  [whatwg-fetch (v2.0.3)](https://github.com/github/fetch#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-whatwg-fetch.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-whatwg-fetch) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-whatwg-fetch.svg)](https://travis-ci.org/npmdoc/node-npmdoc-whatwg-fetch)
#### A window.fetch polyfill.

[![NPM](https://nodei.co/npm/whatwg-fetch.png?downloads=true)](https://www.npmjs.com/package/whatwg-fetch)

[![apidoc](https://npmdoc.github.io/node-npmdoc-whatwg-fetch/build/screenCapture.buildNpmdoc.browser.%2Fhome%2Ftravis%2Fbuild%2Fnpmdoc%2Fnode-npmdoc-whatwg-fetch%2Ftmp%2Fbuild%2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-whatwg-fetch/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-whatwg-fetch/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-whatwg-fetch/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/github/fetch/issues"
    },
    "dependencies": {},
    "description": "A window.fetch polyfill.",
    "devDependencies": {
        "chai": "1.10.0",
        "jshint": "2.8.0",
        "mocha": "2.1.0",
        "mocha-phantomjs-core": "2.0.1",
        "promise-polyfill": "6.0.2",
        "url-search-params": "0.6.1"
    },
    "directories": {},
    "dist": {
        "shasum": "9c84ec2dcf68187ff00bc64e1274b442176e1c84",
        "tarball": "https://registry.npmjs.org/whatwg-fetch/-/whatwg-fetch-2.0.3.tgz"
    },
    "files": [
        "LICENSE",
        "fetch.js"
    ],
    "gitHead": "d4ed806fdcbdeaef707d27f6c88943f0336a647d",
    "homepage": "https://github.com/github/fetch#readme",
    "license": "MIT",
    "main": "fetch.js",
    "maintainers": [
        {
            "name": "mattandrews",
            "email": "matt@mattandre.ws"
        },
        {
            "name": "mislav",
            "email": "mislav.marohnic@gmail.com"
        }
    ],
    "name": "whatwg-fetch",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/github/fetch.git"
    },
    "scripts": {
        "test": "make"
    },
    "version": "2.0.3"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module whatwg-fetch](#apidoc.module.whatwg-fetch)
1.  [function <span class="apidocSignatureSpan">whatwg-fetch.</span>Headers (headers)](#apidoc.element.whatwg-fetch.Headers)
1.  [function <span class="apidocSignatureSpan">whatwg-fetch.</span>Request (input, options)](#apidoc.element.whatwg-fetch.Request)
1.  [function <span class="apidocSignatureSpan">whatwg-fetch.</span>Response (bodyInit, options)](#apidoc.element.whatwg-fetch.Response)
1.  [function <span class="apidocSignatureSpan">whatwg-fetch.</span>fetch (input, init)](#apidoc.element.whatwg-fetch.fetch)
1.  object <span class="apidocSignatureSpan">whatwg-fetch.</span>Headers.prototype
1.  object <span class="apidocSignatureSpan">whatwg-fetch.</span>Request.prototype
1.  object <span class="apidocSignatureSpan">whatwg-fetch.</span>Response.prototype

#### [module whatwg-fetch.Headers](#apidoc.module.whatwg-fetch.Headers)
1.  [function <span class="apidocSignatureSpan">whatwg-fetch.</span>Headers (headers)](#apidoc.element.whatwg-fetch.Headers.Headers)

#### [module whatwg-fetch.Headers.prototype](#apidoc.module.whatwg-fetch.Headers.prototype)
1.  [function <span class="apidocSignatureSpan">whatwg-fetch.Headers.prototype.</span>append (name, value)](#apidoc.element.whatwg-fetch.Headers.prototype.append)
1.  [function <span class="apidocSignatureSpan">whatwg-fetch.Headers.prototype.</span>delete (name)](#apidoc.element.whatwg-fetch.Headers.prototype.delete)
1.  [function <span class="apidocSignatureSpan">whatwg-fetch.Headers.prototype.</span>entries ()](#apidoc.element.whatwg-fetch.Headers.prototype.entries)
1.  [function <span class="apidocSignatureSpan">whatwg-fetch.Headers.prototype.</span>forEach (callback, thisArg)](#apidoc.element.whatwg-fetch.Headers.prototype.forEach)
1.  [function <span class="apidocSignatureSpan">whatwg-fetch.Headers.prototype.</span>get (name)](#apidoc.element.whatwg-fetch.Headers.prototype.get)
1.  [function <span class="apidocSignatureSpan">whatwg-fetch.Headers.prototype.</span>has (name)](#apidoc.element.whatwg-fetch.Headers.prototype.has)
1.  [function <span class="apidocSignatureSpan">whatwg-fetch.Headers.prototype.</span>keys ()](#apidoc.element.whatwg-fetch.Headers.prototype.keys)
1.  [function <span class="apidocSignatureSpan">whatwg-fetch.Headers.prototype.</span>set (name, value)](#apidoc.element.whatwg-fetch.Headers.prototype.set)
1.  [function <span class="apidocSignatureSpan">whatwg-fetch.Headers.prototype.</span>values ()](#apidoc.element.whatwg-fetch.Headers.prototype.values)

#### [module whatwg-fetch.Request](#apidoc.module.whatwg-fetch.Request)
1.  [function <span class="apidocSignatureSpan">whatwg-fetch.</span>Request (input, options)](#apidoc.element.whatwg-fetch.Request.Request)

#### [module whatwg-fetch.Request.prototype](#apidoc.module.whatwg-fetch.Request.prototype)
1.  boolean <span class="apidocSignatureSpan">whatwg-fetch.Request.prototype.</span>bodyUsed
1.  [function <span class="apidocSignatureSpan">whatwg-fetch.Request.prototype.</span>_initBody (body)](#apidoc.element.whatwg-fetch.Request.prototype._initBody)
1.  [function <span class="apidocSignatureSpan">whatwg-fetch.Request.prototype.</span>clone ()](#apidoc.element.whatwg-fetch.Request.prototype.clone)
1.  [function <span class="apidocSignatureSpan">whatwg-fetch.Request.prototype.</span>json ()](#apidoc.element.whatwg-fetch.Request.prototype.json)
1.  [function <span class="apidocSignatureSpan">whatwg-fetch.Request.prototype.</span>text ()](#apidoc.element.whatwg-fetch.Request.prototype.text)

#### [module whatwg-fetch.Response](#apidoc.module.whatwg-fetch.Response)
1.  [function <span class="apidocSignatureSpan">whatwg-fetch.</span>Response (bodyInit, options)](#apidoc.element.whatwg-fetch.Response.Response)
1.  [function <span class="apidocSignatureSpan">whatwg-fetch.Response.</span>error ()](#apidoc.element.whatwg-fetch.Response.error)
1.  [function <span class="apidocSignatureSpan">whatwg-fetch.Response.</span>redirect (url, status)](#apidoc.element.whatwg-fetch.Response.redirect)

#### [module whatwg-fetch.Response.prototype](#apidoc.module.whatwg-fetch.Response.prototype)
1.  boolean <span class="apidocSignatureSpan">whatwg-fetch.Response.prototype.</span>bodyUsed
1.  [function <span class="apidocSignatureSpan">whatwg-fetch.Response.prototype.</span>_initBody (body)](#apidoc.element.whatwg-fetch.Response.prototype._initBody)
1.  [function <span class="apidocSignatureSpan">whatwg-fetch.Response.prototype.</span>clone ()](#apidoc.element.whatwg-fetch.Response.prototype.clone)
1.  [function <span class="apidocSignatureSpan">whatwg-fetch.Response.prototype.</span>json ()](#apidoc.element.whatwg-fetch.Response.prototype.json)
1.  [function <span class="apidocSignatureSpan">whatwg-fetch.Response.prototype.</span>text ()](#apidoc.element.whatwg-fetch.Response.prototype.text)



# <a name="apidoc.module.whatwg-fetch"></a>[module whatwg-fetch](#apidoc.module.whatwg-fetch)

#### <a name="apidoc.element.whatwg-fetch.Headers"></a>[function <span class="apidocSignatureSpan">whatwg-fetch.</span>Headers (headers)](#apidoc.element.whatwg-fetch.Headers)
- description and source-code
```javascript
function Headers(headers) {
  this.map = {}

  if (headers instanceof Headers) {
    headers.forEach(function(value, name) {
      this.append(name, value)
    }, this)
  } else if (Array.isArray(headers)) {
    headers.forEach(function(header) {
      this.append(header[0], header[1])
    }, this)
  } else if (headers) {
    Object.getOwnPropertyNames(headers).forEach(function(name) {
      this.append(name, headers[name])
    }, this)
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.whatwg-fetch.Request"></a>[function <span class="apidocSignatureSpan">whatwg-fetch.</span>Request (input, options)](#apidoc.element.whatwg-fetch.Request)
- description and source-code
```javascript
function Request(input, options) {
  options = options || {}
  var body = options.body

  if (input instanceof Request) {
    if (input.bodyUsed) {
      throw new TypeError('Already read')
    }
    this.url = input.url
    this.credentials = input.credentials
    if (!options.headers) {
      this.headers = new Headers(input.headers)
    }
    this.method = input.method
    this.mode = input.mode
    if (!body && input._bodyInit != null) {
      body = input._bodyInit
      input.bodyUsed = true
    }
  } else {
    this.url = String(input)
  }

  this.credentials = options.credentials || this.credentials || 'omit'
  if (options.headers || !this.headers) {
    this.headers = new Headers(options.headers)
  }
  this.method = normalizeMethod(options.method || this.method || 'GET')
  this.mode = options.mode || this.mode || null
  this.referrer = null

  if ((this.method === 'GET' || this.method === 'HEAD') && body) {
    throw new TypeError('Body not allowed for GET or HEAD requests')
  }
  this._initBody(body)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.whatwg-fetch.Response"></a>[function <span class="apidocSignatureSpan">whatwg-fetch.</span>Response (bodyInit, options)](#apidoc.element.whatwg-fetch.Response)
- description and source-code
```javascript
function Response(bodyInit, options) {
  if (!options) {
    options = {}
  }

  this.type = 'default'
  this.status = 'status' in options ? options.status : 200
  this.ok = this.status >= 200 && this.status < 300
  this.statusText = 'statusText' in options ? options.statusText : 'OK'
  this.headers = new Headers(options.headers)
  this.url = options.url || ''
  this._initBody(bodyInit)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.whatwg-fetch.fetch"></a>[function <span class="apidocSignatureSpan">whatwg-fetch.</span>fetch (input, init)](#apidoc.element.whatwg-fetch.fetch)
- description and source-code
```javascript
fetch = function (input, init) {
  return new Promise(function(resolve, reject) {
    var request = new Request(input, init)
    var xhr = new XMLHttpRequest()

    xhr.onload = function() {
      var options = {
        status: xhr.status,
        statusText: xhr.statusText,
        headers: parseHeaders(xhr.getAllResponseHeaders() || '')
      }
      options.url = 'responseURL' in xhr ? xhr.responseURL : options.headers.get('X-Request-URL')
      var body = 'response' in xhr ? xhr.response : xhr.responseText
      resolve(new Response(body, options))
    }

    xhr.onerror = function() {
      reject(new TypeError('Network request failed'))
    }

    xhr.ontimeout = function() {
      reject(new TypeError('Network request failed'))
    }

    xhr.open(request.method, request.url, true)

    if (request.credentials === 'include') {
      xhr.withCredentials = true
    }

    if ('responseType' in xhr && support.blob) {
      xhr.responseType = 'blob'
    }

    request.headers.forEach(function(value, name) {
      xhr.setRequestHeader(name, value)
    })

    xhr.send(typeof request._bodyInit === 'undefined' ? null : request._bodyInit)
  })
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.whatwg-fetch.Headers"></a>[module whatwg-fetch.Headers](#apidoc.module.whatwg-fetch.Headers)

#### <a name="apidoc.element.whatwg-fetch.Headers.Headers"></a>[function <span class="apidocSignatureSpan">whatwg-fetch.</span>Headers (headers)](#apidoc.element.whatwg-fetch.Headers.Headers)
- description and source-code
```javascript
function Headers(headers) {
  this.map = {}

  if (headers instanceof Headers) {
    headers.forEach(function(value, name) {
      this.append(name, value)
    }, this)
  } else if (Array.isArray(headers)) {
    headers.forEach(function(header) {
      this.append(header[0], header[1])
    }, this)
  } else if (headers) {
    Object.getOwnPropertyNames(headers).forEach(function(name) {
      this.append(name, headers[name])
    }, this)
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.whatwg-fetch.Headers.prototype"></a>[module whatwg-fetch.Headers.prototype](#apidoc.module.whatwg-fetch.Headers.prototype)

#### <a name="apidoc.element.whatwg-fetch.Headers.prototype.append"></a>[function <span class="apidocSignatureSpan">whatwg-fetch.Headers.prototype.</span>append (name, value)](#apidoc.element.whatwg-fetch.Headers.prototype.append)
- description and source-code
```javascript
append = function (name, value) {
  name = normalizeName(name)
  value = normalizeValue(value)
  var oldValue = this.map[name]
  this.map[name] = oldValue ? oldValue+','+value : value
}
```
- example usage
```shell
...

### File upload

'''javascript
var input = document.querySelector('input[type="file"]')

var data = new FormData()
data.append('file', input.files[0])
data.append('user', 'hubot')

fetch('/avatars', {
  method: 'POST',
  body: data
})
'''
...
```

#### <a name="apidoc.element.whatwg-fetch.Headers.prototype.delete"></a>[function <span class="apidocSignatureSpan">whatwg-fetch.Headers.prototype.</span>delete (name)](#apidoc.element.whatwg-fetch.Headers.prototype.delete)
- description and source-code
```javascript
delete = function (name) {
  delete this.map[normalizeName(name)]
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.whatwg-fetch.Headers.prototype.entries"></a>[function <span class="apidocSignatureSpan">whatwg-fetch.Headers.prototype.</span>entries ()](#apidoc.element.whatwg-fetch.Headers.prototype.entries)
- description and source-code
```javascript
entries = function () {
  var items = []
  this.forEach(function(value, name) { items.push([name, value]) })
  return iteratorFor(items)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.whatwg-fetch.Headers.prototype.forEach"></a>[function <span class="apidocSignatureSpan">whatwg-fetch.Headers.prototype.</span>forEach (callback, thisArg)](#apidoc.element.whatwg-fetch.Headers.prototype.forEach)
- description and source-code
```javascript
forEach = function (callback, thisArg) {
  for (var name in this.map) {
    if (this.map.hasOwnProperty(name)) {
      callback.call(thisArg, this.map[name], name, this)
    }
  }
}
```
- example usage
```shell
...
return iterator
  }

  function Headers(headers) {
this.map = {}

if (headers instanceof Headers) {
  headers.forEach(function(value, name) {
    this.append(name, value)
  }, this)
} else if (Array.isArray(headers)) {
  headers.forEach(function(header) {
    this.append(header[0], header[1])
  }, this)
} else if (headers) {
...
```

#### <a name="apidoc.element.whatwg-fetch.Headers.prototype.get"></a>[function <span class="apidocSignatureSpan">whatwg-fetch.Headers.prototype.</span>get (name)](#apidoc.element.whatwg-fetch.Headers.prototype.get)
- description and source-code
```javascript
get = function (name) {
  name = normalizeName(name)
  return this.has(name) ? this.map[name] : null
}
```
- example usage
```shell
...
  })
'''

### Response metadata

'''javascript
fetch('/users.json').then(function(response) {
  console.log(response.headers.get('Content-Type'))
  console.log(response.headers.get('Date'))
  console.log(response.status)
  console.log(response.statusText)
})
'''

### Post form
...
```

#### <a name="apidoc.element.whatwg-fetch.Headers.prototype.has"></a>[function <span class="apidocSignatureSpan">whatwg-fetch.Headers.prototype.</span>has (name)](#apidoc.element.whatwg-fetch.Headers.prototype.has)
- description and source-code
```javascript
has = function (name) {
  return this.map.hasOwnProperty(normalizeName(name))
}
```
- example usage
```shell
...

Headers.prototype['delete'] = function(name) {
  delete this.map[normalizeName(name)]
}

Headers.prototype.get = function(name) {
  name = normalizeName(name)
  return this.has(name) ? this.map[name] : null
}

Headers.prototype.has = function(name) {
  return this.map.hasOwnProperty(normalizeName(name))
}

Headers.prototype.set = function(name, value) {
...
```

#### <a name="apidoc.element.whatwg-fetch.Headers.prototype.keys"></a>[function <span class="apidocSignatureSpan">whatwg-fetch.Headers.prototype.</span>keys ()](#apidoc.element.whatwg-fetch.Headers.prototype.keys)
- description and source-code
```javascript
keys = function () {
  var items = []
  this.forEach(function(value, name) { items.push(name) })
  return iteratorFor(items)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.whatwg-fetch.Headers.prototype.set"></a>[function <span class="apidocSignatureSpan">whatwg-fetch.Headers.prototype.</span>set (name, value)](#apidoc.element.whatwg-fetch.Headers.prototype.set)
- description and source-code
```javascript
set = function (name, value) {
  this.map[normalizeName(name)] = normalizeValue(value)
}
```
- example usage
```shell
...
}

function bufferClone(buf) {
  if (buf.slice) {
    return buf.slice(0)
  } else {
    var view = new Uint8Array(buf.byteLength)
    view.set(new Uint8Array(buf))
    return view.buffer
  }
}

function Body() {
  this.bodyUsed = false
...
```

#### <a name="apidoc.element.whatwg-fetch.Headers.prototype.values"></a>[function <span class="apidocSignatureSpan">whatwg-fetch.Headers.prototype.</span>values ()](#apidoc.element.whatwg-fetch.Headers.prototype.values)
- description and source-code
```javascript
values = function () {
  var items = []
  this.forEach(function(value) { items.push(value) })
  return iteratorFor(items)
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.whatwg-fetch.Request"></a>[module whatwg-fetch.Request](#apidoc.module.whatwg-fetch.Request)

#### <a name="apidoc.element.whatwg-fetch.Request.Request"></a>[function <span class="apidocSignatureSpan">whatwg-fetch.</span>Request (input, options)](#apidoc.element.whatwg-fetch.Request.Request)
- description and source-code
```javascript
function Request(input, options) {
  options = options || {}
  var body = options.body

  if (input instanceof Request) {
    if (input.bodyUsed) {
      throw new TypeError('Already read')
    }
    this.url = input.url
    this.credentials = input.credentials
    if (!options.headers) {
      this.headers = new Headers(input.headers)
    }
    this.method = input.method
    this.mode = input.mode
    if (!body && input._bodyInit != null) {
      body = input._bodyInit
      input.bodyUsed = true
    }
  } else {
    this.url = String(input)
  }

  this.credentials = options.credentials || this.credentials || 'omit'
  if (options.headers || !this.headers) {
    this.headers = new Headers(options.headers)
  }
  this.method = normalizeMethod(options.method || this.method || 'GET')
  this.mode = options.mode || this.mode || null
  this.referrer = null

  if ((this.method === 'GET' || this.method === 'HEAD') && body) {
    throw new TypeError('Body not allowed for GET or HEAD requests')
  }
  this._initBody(body)
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.whatwg-fetch.Request.prototype"></a>[module whatwg-fetch.Request.prototype](#apidoc.module.whatwg-fetch.Request.prototype)

#### <a name="apidoc.element.whatwg-fetch.Request.prototype._initBody"></a>[function <span class="apidocSignatureSpan">whatwg-fetch.Request.prototype.</span>_initBody (body)](#apidoc.element.whatwg-fetch.Request.prototype._initBody)
- description and source-code
```javascript
_initBody = function (body) {
  this._bodyInit = body
  if (!body) {
    this._bodyText = ''
  } else if (typeof body === 'string') {
    this._bodyText = body
  } else if (support.blob && Blob.prototype.isPrototypeOf(body)) {
    this._bodyBlob = body
  } else if (support.formData && FormData.prototype.isPrototypeOf(body)) {
    this._bodyFormData = body
  } else if (support.searchParams && URLSearchParams.prototype.isPrototypeOf(body)) {
    this._bodyText = body.toString()
  } else if (support.arrayBuffer && support.blob && isDataView(body)) {
    this._bodyArrayBuffer = bufferClone(body.buffer)
    // IE 10-11 can't handle a DataView body.
    this._bodyInit = new Blob([this._bodyArrayBuffer])
  } else if (support.arrayBuffer && (ArrayBuffer.prototype.isPrototypeOf(body) || isArrayBufferView(body))) {
    this._bodyArrayBuffer = bufferClone(body)
  } else {
    throw new Error('unsupported BodyInit type')
  }

  if (!this.headers.get('content-type')) {
    if (typeof body === 'string') {
      this.headers.set('content-type', 'text/plain;charset=UTF-8')
    } else if (this._bodyBlob && this._bodyBlob.type) {
      this.headers.set('content-type', this._bodyBlob.type)
    } else if (support.searchParams && URLSearchParams.prototype.isPrototypeOf(body)) {
      this.headers.set('content-type', 'application/x-www-form-urlencoded;charset=UTF-8')
    }
  }
}
```
- example usage
```shell
...
  this.method = normalizeMethod(options.method || this.method || 'GET')
  this.mode = options.mode || this.mode || null
  this.referrer = null

  if ((this.method === 'GET' || this.method === 'HEAD') && body) {
    throw new TypeError('Body not allowed for GET or HEAD requests')
  }
  this._initBody(body)
}

Request.prototype.clone = function() {
  return new Request(this, { body: this._bodyInit })
}

function decode(body) {
...
```

#### <a name="apidoc.element.whatwg-fetch.Request.prototype.clone"></a>[function <span class="apidocSignatureSpan">whatwg-fetch.Request.prototype.</span>clone ()](#apidoc.element.whatwg-fetch.Request.prototype.clone)
- description and source-code
```javascript
clone = function () {
  return new Request(this, { body: this._bodyInit })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.whatwg-fetch.Request.prototype.json"></a>[function <span class="apidocSignatureSpan">whatwg-fetch.Request.prototype.</span>json ()](#apidoc.element.whatwg-fetch.Request.prototype.json)
- description and source-code
```javascript
json = function () {
  return this.text().then(JSON.parse)
}
```
- example usage
```shell
...
'''

### JSON

'''javascript
fetch('/users.json')
  .then(function(response) {
    return response.json()
  }).then(function(json) {
    console.log('parsed json', json)
  }).catch(function(ex) {
    console.log('parsing failed', ex)
  })
'''
...
```

#### <a name="apidoc.element.whatwg-fetch.Request.prototype.text"></a>[function <span class="apidocSignatureSpan">whatwg-fetch.Request.prototype.</span>text ()](#apidoc.element.whatwg-fetch.Request.prototype.text)
- description and source-code
```javascript
text = function () {
  var rejected = consumed(this)
  if (rejected) {
    return rejected
  }

  if (this._bodyBlob) {
    return readBlobAsText(this._bodyBlob)
  } else if (this._bodyArrayBuffer) {
    return Promise.resolve(readArrayBufferAsText(this._bodyArrayBuffer))
  } else if (this._bodyFormData) {
    throw new Error('could not read FormData body as text')
  } else {
    return Promise.resolve(this._bodyText)
  }
}
```
- example usage
```shell
...
https://github.github.io/fetch/.

### HTML

'''javascript
fetch('/users.html')
  .then(function(response) {
    return response.text()
  }).then(function(body) {
    document.body.innerHTML = body
  })
'''

### JSON
...
```



# <a name="apidoc.module.whatwg-fetch.Response"></a>[module whatwg-fetch.Response](#apidoc.module.whatwg-fetch.Response)

#### <a name="apidoc.element.whatwg-fetch.Response.Response"></a>[function <span class="apidocSignatureSpan">whatwg-fetch.</span>Response (bodyInit, options)](#apidoc.element.whatwg-fetch.Response.Response)
- description and source-code
```javascript
function Response(bodyInit, options) {
  if (!options) {
    options = {}
  }

  this.type = 'default'
  this.status = 'status' in options ? options.status : 200
  this.ok = this.status >= 200 && this.status < 300
  this.statusText = 'statusText' in options ? options.statusText : 'OK'
  this.headers = new Headers(options.headers)
  this.url = options.url || ''
  this._initBody(bodyInit)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.whatwg-fetch.Response.error"></a>[function <span class="apidocSignatureSpan">whatwg-fetch.Response.</span>error ()](#apidoc.element.whatwg-fetch.Response.error)
- description and source-code
```javascript
error = function () {
  var response = new Response(null, {status: 0, statusText: ''})
  response.type = 'error'
  return response
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.whatwg-fetch.Response.redirect"></a>[function <span class="apidocSignatureSpan">whatwg-fetch.Response.</span>redirect (url, status)](#apidoc.element.whatwg-fetch.Response.redirect)
- description and source-code
```javascript
redirect = function (url, status) {
  if (redirectStatuses.indexOf(status) === -1) {
    throw new RangeError('Invalid status code')
  }

  return new Response(null, {status: status, headers: {location: url}})
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.whatwg-fetch.Response.prototype"></a>[module whatwg-fetch.Response.prototype](#apidoc.module.whatwg-fetch.Response.prototype)

#### <a name="apidoc.element.whatwg-fetch.Response.prototype._initBody"></a>[function <span class="apidocSignatureSpan">whatwg-fetch.Response.prototype.</span>_initBody (body)](#apidoc.element.whatwg-fetch.Response.prototype._initBody)
- description and source-code
```javascript
_initBody = function (body) {
  this._bodyInit = body
  if (!body) {
    this._bodyText = ''
  } else if (typeof body === 'string') {
    this._bodyText = body
  } else if (support.blob && Blob.prototype.isPrototypeOf(body)) {
    this._bodyBlob = body
  } else if (support.formData && FormData.prototype.isPrototypeOf(body)) {
    this._bodyFormData = body
  } else if (support.searchParams && URLSearchParams.prototype.isPrototypeOf(body)) {
    this._bodyText = body.toString()
  } else if (support.arrayBuffer && support.blob && isDataView(body)) {
    this._bodyArrayBuffer = bufferClone(body.buffer)
    // IE 10-11 can't handle a DataView body.
    this._bodyInit = new Blob([this._bodyArrayBuffer])
  } else if (support.arrayBuffer && (ArrayBuffer.prototype.isPrototypeOf(body) || isArrayBufferView(body))) {
    this._bodyArrayBuffer = bufferClone(body)
  } else {
    throw new Error('unsupported BodyInit type')
  }

  if (!this.headers.get('content-type')) {
    if (typeof body === 'string') {
      this.headers.set('content-type', 'text/plain;charset=UTF-8')
    } else if (this._bodyBlob && this._bodyBlob.type) {
      this.headers.set('content-type', this._bodyBlob.type)
    } else if (support.searchParams && URLSearchParams.prototype.isPrototypeOf(body)) {
      this.headers.set('content-type', 'application/x-www-form-urlencoded;charset=UTF-8')
    }
  }
}
```
- example usage
```shell
...
  this.method = normalizeMethod(options.method || this.method || 'GET')
  this.mode = options.mode || this.mode || null
  this.referrer = null

  if ((this.method === 'GET' || this.method === 'HEAD') && body) {
    throw new TypeError('Body not allowed for GET or HEAD requests')
  }
  this._initBody(body)
}

Request.prototype.clone = function() {
  return new Request(this, { body: this._bodyInit })
}

function decode(body) {
...
```

#### <a name="apidoc.element.whatwg-fetch.Response.prototype.clone"></a>[function <span class="apidocSignatureSpan">whatwg-fetch.Response.prototype.</span>clone ()](#apidoc.element.whatwg-fetch.Response.prototype.clone)
- description and source-code
```javascript
clone = function () {
  return new Response(this._bodyInit, {
    status: this.status,
    statusText: this.statusText,
    headers: new Headers(this.headers),
    url: this.url
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.whatwg-fetch.Response.prototype.json"></a>[function <span class="apidocSignatureSpan">whatwg-fetch.Response.prototype.</span>json ()](#apidoc.element.whatwg-fetch.Response.prototype.json)
- description and source-code
```javascript
json = function () {
  return this.text().then(JSON.parse)
}
```
- example usage
```shell
...
'''

### JSON

'''javascript
fetch('/users.json')
  .then(function(response) {
    return response.json()
  }).then(function(json) {
    console.log('parsed json', json)
  }).catch(function(ex) {
    console.log('parsing failed', ex)
  })
'''
...
```

#### <a name="apidoc.element.whatwg-fetch.Response.prototype.text"></a>[function <span class="apidocSignatureSpan">whatwg-fetch.Response.prototype.</span>text ()](#apidoc.element.whatwg-fetch.Response.prototype.text)
- description and source-code
```javascript
text = function () {
  var rejected = consumed(this)
  if (rejected) {
    return rejected
  }

  if (this._bodyBlob) {
    return readBlobAsText(this._bodyBlob)
  } else if (this._bodyArrayBuffer) {
    return Promise.resolve(readArrayBufferAsText(this._bodyArrayBuffer))
  } else if (this._bodyFormData) {
    throw new Error('could not read FormData body as text')
  } else {
    return Promise.resolve(this._bodyText)
  }
}
```
- example usage
```shell
...
https://github.github.io/fetch/.

### HTML

'''javascript
fetch('/users.html')
  .then(function(response) {
    return response.text()
  }).then(function(body) {
    document.body.innerHTML = body
  })
'''

### JSON
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
