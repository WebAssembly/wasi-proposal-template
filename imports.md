<h1><a name="imports">World imports</a></h1>
<ul>
<li>Imports:
<ul>
<li>interface <a href="#wasi:example_api_package_example_dep_interface"><code>wasi:example-api-package/example-dep-interface</code></a></li>
<li>interface <a href="#wasi:example_package_example_interface"><code>wasi:example-package/example-interface</code></a></li>
</ul>
</li>
</ul>
<h2><a name="wasi:example_api_package_example_dep_interface"></a>Import interface wasi:example-api-package/example-dep-interface</h2>
<hr />
<h3>Types</h3>
<h4><a name="example_dep_type"></a><code>type example-dep-type</code></h4>
<p><code>u32</code></p>
<p>
## <a name="wasi:example_package_example_interface"></a>Import interface wasi:example-package/example-interface
<p>Instructions for filling in this file:</p>
<ul>
<li>
<p>Delete all these <code>//</code> comments, up to the first <code>///</code> comment.</p>
</li>
<li>
<p>Replace the remaining contents below with <a href="https://github.com/WebAssembly/component-model/blob/main/design/mvp/WIT.md">Wit</a> code describing
<code>interface</code>s and/or <code>world</code>s, using the same formatting style.</p>
</li>
</ul>
<p>If you want to include examples of the API in use, these should be in the
README.md at the root of the repository and linked to from this file.</p>
<p>Short interface description.</p>
<p>Explanation for developers using the interface API. It should include an
overview of the API as a whole as well as call out notable items in it,
for example <a href="#example_api_type"><code>example-api-type</code></a> and <a href="#example_api_function"><code>example-api-function</code></a>.</p>
<hr />
<h3>Types</h3>
<h4><a name="example_dep_type"></a><code>type example-dep-type</code></h4>
<p><a href="#example_dep_type"><a href="#example_dep_type"><code>example-dep-type</code></a></a></p>
<p>
#### <a name="example_api_type"></a>`record example-api-type`
<p>Short type description</p>
<p>Explanation for developers using this type. It may be useful to give
some examples of places in the API where the type is used, such as in
the arguments and return type of <a href="#example_api_function"><code>example-api-function</code></a>.</p>
<details>
<summary>Detailed specification</summary>
More rigorous specification details for implementers go here, if needed.
The intention is to keep the developer-oriented docs focused on things that
most developers will need to be aware of, while putting bulkier descriptions
of precise behavior here.
</details>
<h5>Record Fields</h5>
<ul>
<li>
<p><a name="example_api_type.field0"></a><code>field0</code>: <code>u64</code></p>
<p>A description of a field.
</li>
<li>
<p><a name="example_api_type.field1"></a><code>field1</code>: <code>string</code></p>
<p>A description of another field.
</li>
</ul>
<hr />
<h3>Functions</h3>
<h4><a name="example_api_function"></a><code>example-api-function: func</code></h4>
<p>Short function description</p>
<p>Explanation for developers using the API. This should describe the
arguments which in this function are <code>arg0</code>, <code>arg1</code>, and <code>arg2</code>, and the
return value.</p>
<details>
<summary>Detailed specification</summary>
Similar to the details section above, this is meant for more rigorous
specification details for implementors. This may explain what a compliant
implementation MUST do, such as never returning an earlier result from a
later call, for example.
</details>
<h5>Params</h5>
<ul>
<li><a name="example_api_function.arg0"></a><code>arg0</code>: <a href="#example_api_type"><a href="#example_api_type"><code>example-api-type</code></a></a></li>
<li><a name="example_api_function.arg1"></a><code>arg1</code>: <code>string</code></li>
<li><a name="example_api_function.arg2"></a><code>arg2</code>: <a href="#example_dep_type"><a href="#example_dep_type"><code>example-dep-type</code></a></a></li>
</ul>
<h5>Return values</h5>
<ul>
<li><a name="example_api_function.0"></a> result&lt;<a href="#example_api_type"><a href="#example_api_type"><code>example-api-type</code></a></a>&gt;</li>
</ul>
