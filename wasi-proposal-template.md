<h1><a name="wasi_proposal_template">World wasi-proposal-template</a></h1>
<ul>
<li>Imports:
<ul>
<li>interface <a href="#proposal_interface_name"><code>proposal-interface-name</code></a></li>
</ul>
</li>
</ul>
<h2><a name="proposal_interface_name">Import interface proposal-interface-name</a></h2>
<p>Short interface description.</p>
<p>Explanation for developers using the interface API. It should include an
overview of the API as a whole as well as call out notable items in it,
for example <a href="#example_api_type"><code>example-api-type</code></a> and <a href="#example_api_function"><code>example-api-function</code></a>.</p>
<hr />
<h3>Types</h3>
<h4><a name="example_api_type"><code>record example-api-type</code></a></h4>
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
<p><a name="example_api_type.property0"><code>property0</code></a>: <code>u64</code></p>
<p>A description of a property.
</li>
<li>
<p><a name="example_api_type.property1"><code>property1</code></a>: <code>string</code></p>
<p>A description of another property.
</li>
</ul>
<hr />
<h3>Functions</h3>
<h4><a name="example_api_function"><code>example-api-function: func</code></a></h4>
<p>Short function description</p>
<p>Explanation for developers using the API. This should describe the
arguments which in this function are <code>arg0</code> and <code>arg1</code> and the return value.</p>
<details>
<summary>Detailed specification</summary>
Similar to the details section above, this is meant for more rigorous
specification details for implementors. This may explain what a compliant
implementation MUST do, such as never returning an earlier result from a
later call, for example.
</details>
<h5>Params</h5>
<ul>
<li><a name="example_api_function.arg0"><code>arg0</code></a>: <a href="#example_api_type"><a href="#example_api_type"><code>example-api-type</code></a></a></li>
<li><a name="example_api_function.arg1"><code>arg1</code></a>: <code>string</code></li>
</ul>
<h5>Return values</h5>
<ul>
<li><a name="example_api_function.0"></a> result&lt;<a href="#example_api_type"><a href="#example_api_type"><code>example-api-type</code></a></a>&gt;</li>
</ul>
