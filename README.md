# IAM-Policy-From-CFN
Generates IAM actions to save time in AWS

The idea of this is to build a Python script. It will take the input of a YAML (JSON should be easily supported too), and parse the resources section.
For each item in there, it should add the create and update actions that are required.

It might be that this gets complicated with certain types of resources

alternative idea

given a load of CloudTrail logs, build an IAM policy that permits all actions in there done by cloudformation?
