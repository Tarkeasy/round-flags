# round-flags

## round-flags - provides a round-shaped collection of svg format flags, you can use it with any library or framework you work with.
### Collection of over 200 flags

## Example with react
```
import React from 'react;
import { GB } from 'round-flags';

function Example () {
  return <img src={GB} />
}
```
<img src="https://image.flaticon.com/icons/svg/197/197374.svg" width="100" height="100" />

### Also you can import a flag by providing data.
```
import React from 'react;
import PropTypes from 'prop-types';
import * as images from 'round-flags';

function Example (props) {
  // props just a string 'UA'
  return <img src={images[props.UA]} />
}

Example.propTypes = {
  UA: PropTypes.string,
};
```
<img src="https://image.flaticon.com/icons/svg/197/197572.svg" width="100" height="100" />

### You can import a flag only providing ALPHA-2 code of country.

### Example
```
import { US } from 'round-flags'; /// Flag of United States
import { ES } from 'round-flags'; /// Flag of Spain

```
