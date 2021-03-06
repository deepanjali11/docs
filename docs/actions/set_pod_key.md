# set_pod_key


Sets a value for a key with cocoapods-keys




> Adds a key to [cocoapods-keys](https://github.com/orta/cocoapods-keys)


set_pod_key |
-----|----
Supported platforms | ios, mac
Author | @marcelofabri



**1 Example**

```ruby
set_pod_key(
  key: "APIToken",
  value: "1234",
  project: "MyProject"
)
```





**Parameters**

Key | Description
----|------------
  `use_bundle_exec` | Use bundle exec when there is a Gemfile presented
  `key` | The key to be saved with cocoapods-keys
  `value` | The value to be saved with cocoapods-keys
  `project` | The project name




<hr />
To show the documentation in your terminal, run
```no-highlight
fastlane action set_pod_key
```

<a href="https://github.com/fastlane/fastlane/blob/master/fastlane/lib/fastlane/actions/set_pod_key.rb" target="_blank">View source code</a>

<hr />

<a href="/actions"><b>Back to actions</b></a>
