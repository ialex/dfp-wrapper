# dfp-wrapper

### 1.4.0

- Add option to specify where the config files live
- fixes bug on Add custom criteria

### 1.3.0
- Adds `getCriteriaValues` for querying criteria values as full objects.
- Adds `getCriteriaValueId` for querying criteria values and returning the first id.
- Deprecates `getCriteriaValue` for querying criteria values and returning the first id.

### 1.2.1
- Updated node-google-dfp to 0.2.1

### 1.2.0
BREAKING CHANGES
- Refactor logic for querying DFP for records.
- Refactor caching and lookup strategy for custom targeting criteria methods.
- Add methods for querying and creating report jobs.

### 1.1.0
- Add methods for querying and updating line-item-creative-associations.

### 1.0.1
- Bug fix, enable local storage for caching.

### 1.0.0
- Bring over functions from `spanishdict/example-line-item-generator/lib/dfp.js` and `spanishdict/example-line-item-generator/lib/user.js`.
- Add functions for generating reports.
