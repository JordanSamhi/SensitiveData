This repository includes a list of sensitive API methods, currently of the Android API.
This list is meant to be expanded as a community effort.
The file containing the API methods is structured as xml-file.

A single method is annotated with the following information:
- signature: a unique method signature in Soot notation,
- parameter_index: the parameter index of the sensitive data, starting with 0, or -1 for the return value,
- sensitiveness: the category of sensitiveness regarding to our paper (further reference will be added once the paper has been published),
- regulations/regulation: contains the legal privacy frameworks, e.g., the GDPR, under which the method is sensitive,
- categories/category: the category of sensitive data, e.g., personal identifiers, device identifiers, or images/pictures.
