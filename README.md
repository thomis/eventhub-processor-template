eventhub-processor-template
===========================

Template to create a new Event Hub Processor

This will get cloned when running `eh generate_processor`. E.g. `eh generate_processor inventory runner` will clone this repository to a new directory `inventory.runner`, run erb where applicable and rename files with the following placeholders:

* processor_module_name (e.g. Inventory)
* processor_class_name (e.g. Runner)
* underscored_processor_module_name (e.g. inventory)
* underscored_processor_class_name (e.g. runner)
