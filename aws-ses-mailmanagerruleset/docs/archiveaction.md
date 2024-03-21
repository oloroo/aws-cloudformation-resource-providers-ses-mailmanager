# AWS::SES::MailManagerRuleSet ArchiveAction

## Syntax

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON

<pre>
{
    "<a href="#targetarchive" title="TargetArchive">TargetArchive</a>" : <i>String</i>
}
</pre>

### YAML

<pre>
<a href="#targetarchive" title="TargetArchive">TargetArchive</a>: <i>String</i>
</pre>

## Properties

#### TargetArchive

_Required_: Yes

_Type_: String

_Minimum Length_: <code>1</code>

_Maximum Length_: <code>2048</code>

_Pattern_: <code>^[a-zA-Z0-9:_/+=,@.#-]+$</code>

_Update requires_: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)