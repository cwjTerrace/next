{"title":"弹窗便捷方法","meta":{"title":"弹窗便捷方法","description":"\n<p>可以通过<code>Message.success</code>等静态方法来方便的显示指定类型的信息弹窗。</p>\n","order":"6"},"codes":{"jsx":"import { Message, Button } from '@alifd/next';\n\n\nconst showSuccess = () => Message.success('success');\nconst showWarning = () => Message.warning('warning');\nconst showError = () => Message.error('error');\nconst showNotice = () => Message.notice('notice');\nconst showHelp = () => Message.help('help');\nconst showLoading = () => Message.loading('loading');\n\nReactDOM.render(\n    <div className=\"message-toast-quick-demo\">\n        <Button onClick={showSuccess}>success</Button>\n        <Button onClick={showWarning}>warning</Button>\n        <Button onClick={showError}>error</Button>\n        <Button onClick={showNotice}>notice</Button>\n        <Button onClick={showHelp}>help</Button>\n        <Button onClick={showLoading}>loading</Button>\n    </div>, mountNode);\n","css":".message-toast-quick-demo .next-btn.next-medium {\n    margin-right: 10px;\n    margin-bottom: 10px;\n}\n"},"body":"\n\n````jsx\nimport { Message, Button } from '@alifd/next';\n\n\nconst showSuccess = () => Message.success('success');\nconst showWarning = () => Message.warning('warning');\nconst showError = () => Message.error('error');\nconst showNotice = () => Message.notice('notice');\nconst showHelp = () => Message.help('help');\nconst showLoading = () => Message.loading('loading');\n\nReactDOM.render(\n    <div className=\"message-toast-quick-demo\">\n        <Button onClick={showSuccess}>success</Button>\n        <Button onClick={showWarning}>warning</Button>\n        <Button onClick={showError}>error</Button>\n        <Button onClick={showNotice}>notice</Button>\n        <Button onClick={showHelp}>help</Button>\n        <Button onClick={showLoading}>loading</Button>\n    </div>, mountNode);\n````\n\n````css\n.message-toast-quick-demo .next-btn.next-medium {\n    margin-right: 10px;\n    margin-bottom: 10px;\n}\n````","html":"<script>(function(){'use strict';\n\nvar _next = require('@alifd/next');\n\nvar showSuccess = function showSuccess() {\n    return _next.Message.success('success');\n};\nvar showWarning = function showWarning() {\n    return _next.Message.warning('warning');\n};\nvar showError = function showError() {\n    return _next.Message.error('error');\n};\nvar showNotice = function showNotice() {\n    return _next.Message.notice('notice');\n};\nvar showHelp = function showHelp() {\n    return _next.Message.help('help');\n};\nvar showLoading = function showLoading() {\n    return _next.Message.loading('loading');\n};\n\nReactDOM.render(React.createElement(\n    'div',\n    { className: 'message-toast-quick-demo' },\n    React.createElement(\n        _next.Button,\n        { onClick: showSuccess },\n        'success'\n    ),\n    React.createElement(\n        _next.Button,\n        { onClick: showWarning },\n        'warning'\n    ),\n    React.createElement(\n        _next.Button,\n        { onClick: showError },\n        'error'\n    ),\n    React.createElement(\n        _next.Button,\n        { onClick: showNotice },\n        'notice'\n    ),\n    React.createElement(\n        _next.Button,\n        { onClick: showHelp },\n        'help'\n    ),\n    React.createElement(\n        _next.Button,\n        { onClick: showLoading },\n        'loading'\n    )\n), mountNode);})()</script><div class=\"highlight\"><pre class=\"language-jsx\"><code class=\"language-jsx\"><span class=\"token keyword\">import</span> <span class=\"token punctuation\">{</span> Message<span class=\"token punctuation\">,</span> Button <span class=\"token punctuation\">}</span> <span class=\"token keyword\">from</span> <span class=\"token string\">'@alifd/next'</span><span class=\"token punctuation\">;</span>\n\n\n<span class=\"token keyword\">const</span> <span class=\"token function-variable function\">showSuccess</span> <span class=\"token operator\">=</span> <span class=\"token punctuation\">(</span><span class=\"token punctuation\">)</span> <span class=\"token operator\">=></span> Message<span class=\"token punctuation\">.</span><span class=\"token function\">success</span><span class=\"token punctuation\">(</span><span class=\"token string\">'success'</span><span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span>\n<span class=\"token keyword\">const</span> <span class=\"token function-variable function\">showWarning</span> <span class=\"token operator\">=</span> <span class=\"token punctuation\">(</span><span class=\"token punctuation\">)</span> <span class=\"token operator\">=></span> Message<span class=\"token punctuation\">.</span><span class=\"token function\">warning</span><span class=\"token punctuation\">(</span><span class=\"token string\">'warning'</span><span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span>\n<span class=\"token keyword\">const</span> <span class=\"token function-variable function\">showError</span> <span class=\"token operator\">=</span> <span class=\"token punctuation\">(</span><span class=\"token punctuation\">)</span> <span class=\"token operator\">=></span> Message<span class=\"token punctuation\">.</span><span class=\"token function\">error</span><span class=\"token punctuation\">(</span><span class=\"token string\">'error'</span><span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span>\n<span class=\"token keyword\">const</span> <span class=\"token function-variable function\">showNotice</span> <span class=\"token operator\">=</span> <span class=\"token punctuation\">(</span><span class=\"token punctuation\">)</span> <span class=\"token operator\">=></span> Message<span class=\"token punctuation\">.</span><span class=\"token function\">notice</span><span class=\"token punctuation\">(</span><span class=\"token string\">'notice'</span><span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span>\n<span class=\"token keyword\">const</span> <span class=\"token function-variable function\">showHelp</span> <span class=\"token operator\">=</span> <span class=\"token punctuation\">(</span><span class=\"token punctuation\">)</span> <span class=\"token operator\">=></span> Message<span class=\"token punctuation\">.</span><span class=\"token function\">help</span><span class=\"token punctuation\">(</span><span class=\"token string\">'help'</span><span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span>\n<span class=\"token keyword\">const</span> <span class=\"token function-variable function\">showLoading</span> <span class=\"token operator\">=</span> <span class=\"token punctuation\">(</span><span class=\"token punctuation\">)</span> <span class=\"token operator\">=></span> Message<span class=\"token punctuation\">.</span><span class=\"token function\">loading</span><span class=\"token punctuation\">(</span><span class=\"token string\">'loading'</span><span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span>\n\nReactDOM<span class=\"token punctuation\">.</span><span class=\"token function\">render</span><span class=\"token punctuation\">(</span>\n    <span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>div</span> <span class=\"token attr-name\">className</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>message-toast-quick-demo<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Button</span></span> <span class=\"token attr-name\">onClick</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span>showSuccess<span class=\"token punctuation\">}</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">success</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Button</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Button</span></span> <span class=\"token attr-name\">onClick</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span>showWarning<span class=\"token punctuation\">}</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">warning</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Button</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Button</span></span> <span class=\"token attr-name\">onClick</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span>showError<span class=\"token punctuation\">}</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">error</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Button</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Button</span></span> <span class=\"token attr-name\">onClick</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span>showNotice<span class=\"token punctuation\">}</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">notice</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Button</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Button</span></span> <span class=\"token attr-name\">onClick</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span>showHelp<span class=\"token punctuation\">}</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">help</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Button</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Button</span></span> <span class=\"token attr-name\">onClick</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span>showLoading<span class=\"token punctuation\">}</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">loading</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Button</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token punctuation\">,</span> mountNode<span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span></code></pre></div><style type=\"text/css\">.message-toast-quick-demo .next-btn.next-medium {\n    margin-right: 10px;\n    margin-bottom: 10px;\n}</style><div class=\"highlight\"><pre class=\"language-css\"><code class=\"language-css\"><span class=\"token selector\">.message-toast-quick-demo .next-btn.next-medium</span> <span class=\"token punctuation\">{</span>\n    <span class=\"token property\">margin-right</span><span class=\"token punctuation\">:</span> 10px<span class=\"token punctuation\">;</span>\n    <span class=\"token property\">margin-bottom</span><span class=\"token punctuation\">:</span> 10px<span class=\"token punctuation\">;</span>\n<span class=\"token punctuation\">}</span></code></pre></div>"}