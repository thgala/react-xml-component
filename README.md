## Overview

Simple __react__ component for rendering custom tags. Initially designed to be rendered on `server`, also working on a `client`.

___

_Technologies:_

- _`typescript`_
- _`jest`_

### Installation

```
yarn add react-xml-component
```

### Usage

```ts
import { XML } from 'react-xml-component';

/**
 * ...
 */

/**
 * Inside render method
 */
 
<XML
  name="any:name"
  attrList={[
    { 'some:weird': 'stuff' },
    { 'another-react': 'component' },
    { 'Support': 'typescript' }
  ]}
>
  <XML name="children:data">
    <XML name="first:name">Konstantin</XML>
  </XML>
</XML>

/**
 * ...
 */

/**
 * Output
 */
 
```
