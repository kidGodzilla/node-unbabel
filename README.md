Unbabel API for Node
===========

This Node.js module provides access to the [Unbabel API](http://developers.unbabel.com/) for ordering translations.

Installation
----------

Install via [npm](http://npmjs.org/)

    npm install unabebl --save


Initialize Unbabel with your username and API key. If querying the Unbabel sandbox, set `sandbox` to true.

    var unbabel = require('unbabel')(username, apiKey, sandbox);


Endpoints
----------
  
- All callbacks are passed an error and response: `callback(err, res)`.
- Supports camelCase and underscore naming conventions for option fields.
- Please refer to Unbabel's [API Docs](http://developers.unbabel.com/) for endpoint details.
  
Endpoints...

    unbabel.languagePair(callback);
    
    unbabel.tone(callback);
    
    unbabel.topic(callback);


Contribute
----------

Forks and pull requests welcome!

TODO
----------
* Add tests


Author
----------

Brandon Paton. Email me if you have any questions: [bp@brandonpaton.com](mailto:bp@brandonpaton.com). Supported by [Localize.js](https://localizejs.com/).
