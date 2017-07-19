# Problem statement
creates an azure eventhub namespace authorization rule (if it doesn't already exist)

# Example usage

> note: in examples, VERSION represents a version of the azure.eventhub.namespace.authrule.create pkg

## install

```shell
opctl pkg install github.com/opspec-pkgs/azure.eventhub.namespace.authrule.create#VERSION
```

## run

```
opctl run github.com/opspec-pkgs/azure.eventhub.namespace.authrule.create#VERSION
```

## compose

```yaml
op:
  pkg: { ref: github.com/opspec-pkgs/azure.eventhub.namespace.authrule.create#VERSION }
  inputs: 
    subscriptionId:
    loginId:
    loginSecret:
    loginTenantId:
    eventHub:
    name:
    namespace:
    resourceGroup:
    rights:
    # begin optional args
    loginType:
    # end optional args
```

# Support

join us on [![Slack](https://opspec-slackin.herokuapp.com/badge.svg)](https://opspec-slackin.herokuapp.com/)
or [open an issue](https://github.com/opspec-pkgs/azure.eventhub.namespace.authrule.create/issues)

