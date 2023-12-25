[![ci](https://github.com/thomis/eventhub-processor-template/actions/workflows/ci.yml/badge.svg)](https://github.com/thomis/eventhub-processor-template/actions/workflows/ci.yml)

**Note**

eventhub-processor-template has been retired and will not be further maintained.

eventhub-processor-template
===========================

Template to create a new Event Hub Processor.

This will get cloned when running `eh generate processor`. E.g. `eh generate processor inventory runner` will clone this repository to a new directory `inventory.runner`, run erb where applicable and rename files with the following placeholders:

* processor_module_name (e.g. Inventory)
* processor_class_name (e.g. Runner)
* underscored_processor_module_name (e.g. inventory)
* underscored_processor_class_name (e.g. runner)

Please also refer to https://github.com/thomis/eventhub-command.
