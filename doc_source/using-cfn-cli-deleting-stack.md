# Deleting a Stack<a name="using-cfn-cli-deleting-stack"></a>

To delete a stack, you run the `[aws cloudformation delete\-stack](http://docs.aws.amazon.com/cli/latest/reference/cloudformation/delete-stack.html)` command\. You must specify the name of the stack that you want to delete\. When you delete a stack, you delete the stack and all of its resources\.

The following example deletes the `myteststack` stack:

```
aws cloudformation delete-stack --stack-name myteststack
```

**Note**  
You cannot delete a stack that has termination protection enabled\. For more information, see [Protecting a Stack From Being Deleted](using-cfn-protect-stacks.md)