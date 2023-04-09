## bumawiki-editor

부마위키 문서 편집기 라이브러리입니다.

use :

```
yarn add bumawiki-editor

or

npm install bumawiki-editor
```

```jsx
import bumawikiEditor from 'bumawiki-editor'
import React from 'react'

const App = () => {
	const [contents, setContents] = React.useState('')

	const htmlConfig = {
		__html: bumawikiEditor(contents),
	}

	return <div dangerouslySetInnerHTML={htmlConfig} />
}
```
