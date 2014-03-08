chef-ssh-auth-sock Cookbook
===========================

Use local `SSH_AUTH_SOCK` enviroments, when you run `vagrant up`.
Makes it possible to clone from the private repository.


*SEE* [http://stackoverflow.com/questions/7211287/use-ssh-keys-with-passphrase-on-a-vagrantchef-setup]


Usage
-----
#### chef-ssh-auth-sock::default

Just include `chef-ssh-auth-sock` in your node's `run_list`:

```json
{
  "name":"my_node",
  "run_list": [
    "recipe[chef-ssh-auth-sock]"
  ]
}
```

Contributing
------------

1. Fork the repository on Github
2. Create a named feature branch (like `add_component_x`)
3. Write your change
4. Write tests for your change (if applicable)
5. Run the tests, ensuring they all pass
6. Submit a Pull Request using Github

License and Authors
-------------------
Authors: w1mvy
