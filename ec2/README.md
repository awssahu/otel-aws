Create IAM Policy

See the Permissions section for the permissions required and IAM policy setup steps.


Attach the IAM Policy

    Open the IAM console.
    In the navigation pane, choose Roles, and then choose Create role.
    In the Select type of trusted entity section, choose AWS service.
    For Choose a use case, select EC2, then choose Next: Permission.
    For Attach permissions policies, choose the policy AWSDistroOpenTelemetryPolicy, and then choose Next: Tags.
    Choose Next: Review.
    On the Review page, type AWSDistroOpenTelemetryRole for the Name, and then choose Create role.
