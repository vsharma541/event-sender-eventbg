# event-sender-eventbg

This repo is for configuring source event-bridge that will consist of a lambda and an eventbridge within account lets say accountid - 233886345769. Lambda will send event to the eventbus. Eventbus of another account with accountid lets say - https://354918362658.signin.aws.amazon.com/console, will register as target for this eventbus.
So, events from eventbus in accountid 233886345769 will be sent to eventbus of account with accountid - 354918362658
