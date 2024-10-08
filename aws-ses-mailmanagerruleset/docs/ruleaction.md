# AWS::SES::MailManagerRuleSet RuleAction

## Syntax

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON

<pre>
{
    "<a href="#drop" title="Drop">Drop</a>" : <i>Map</i>,
    "<a href="#relay" title="Relay">Relay</a>" : <i><a href="relayaction.md">RelayAction</a></i>,
    "<a href="#archive" title="Archive">Archive</a>" : <i><a href="archiveaction.md">ArchiveAction</a></i>,
    "<a href="#writetos3" title="WriteToS3">WriteToS3</a>" : <i><a href="s3action.md">S3Action</a></i>,
    "<a href="#send" title="Send">Send</a>" : <i><a href="sendaction.md">SendAction</a></i>,
    "<a href="#addheader" title="AddHeader">AddHeader</a>" : <i><a href="addheaderaction.md">AddHeaderAction</a></i>,
    "<a href="#replacerecipient" title="ReplaceRecipient">ReplaceRecipient</a>" : <i><a href="replacerecipientaction.md">ReplaceRecipientAction</a></i>,
    "<a href="#delivertomailbox" title="DeliverToMailbox">DeliverToMailbox</a>" : <i><a href="delivertomailboxaction.md">DeliverToMailboxAction</a></i>
}
</pre>

### YAML

<pre>
<a href="#drop" title="Drop">Drop</a>: <i>Map</i>
<a href="#relay" title="Relay">Relay</a>: <i><a href="relayaction.md">RelayAction</a></i>
<a href="#archive" title="Archive">Archive</a>: <i><a href="archiveaction.md">ArchiveAction</a></i>
<a href="#writetos3" title="WriteToS3">WriteToS3</a>: <i><a href="s3action.md">S3Action</a></i>
<a href="#send" title="Send">Send</a>: <i><a href="sendaction.md">SendAction</a></i>
<a href="#addheader" title="AddHeader">AddHeader</a>: <i><a href="addheaderaction.md">AddHeaderAction</a></i>
<a href="#replacerecipient" title="ReplaceRecipient">ReplaceRecipient</a>: <i><a href="replacerecipientaction.md">ReplaceRecipientAction</a></i>
<a href="#delivertomailbox" title="DeliverToMailbox">DeliverToMailbox</a>: <i><a href="delivertomailboxaction.md">DeliverToMailboxAction</a></i>
</pre>

## Properties

#### Drop

_Required_: Yes

_Type_: Map

_Update requires_: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

#### Relay

_Required_: Yes

_Type_: <a href="relayaction.md">RelayAction</a>

_Update requires_: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

#### Archive

_Required_: Yes

_Type_: <a href="archiveaction.md">ArchiveAction</a>

_Update requires_: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

#### WriteToS3

_Required_: Yes

_Type_: <a href="s3action.md">S3Action</a>

_Update requires_: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

#### Send

_Required_: Yes

_Type_: <a href="sendaction.md">SendAction</a>

_Update requires_: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

#### AddHeader

_Required_: Yes

_Type_: <a href="addheaderaction.md">AddHeaderAction</a>

_Update requires_: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

#### ReplaceRecipient

_Required_: Yes

_Type_: <a href="replacerecipientaction.md">ReplaceRecipientAction</a>

_Update requires_: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

#### DeliverToMailbox

_Required_: Yes

_Type_: <a href="delivertomailboxaction.md">DeliverToMailboxAction</a>

_Update requires_: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)
