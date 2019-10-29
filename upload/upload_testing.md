# Rescale File Upload Testing

We want you to write an automated UI test for uploading a file to the
Rescale platform and also provide some answers to some additional discussion
topics.

## Deliverables

1. Register for a free account on https://platform.rescale.com/
1. Select `New Job` from the top nav (https://platform.rescale.com/jobs/new-job/setup/input-files/). There is an `Upload from this computer` button displayed in the `Specify Inputs` section of the UI
(https://platform.rescale.com/files/) that allows the user to upload a new file
to the platform. Write an automated UI test using whatever framework you want
to verify that a new file can be uploaded successfully.

### Discussion Topics
* The automated UI test only covers the "happy path". Please describe
in detail what other types of automated tests you would set up to verify that
the file upload feature is working as expected.
* In the top nav, the Transfers menu item contains a toggle button for `Basic`
and `Enhanced`.

    ![transfer method](transfer_method.png)

    * What is the difference between these two options? (Hint: look at the
    browser debug toolbar)
    * How do these different methods compare to uploading a file through the
    API? ([API documentation](https://engineering.rescale.com/api-docs/))
    * What security or additional testing concerns do you have with these
    two approaches?

## Guidelines
* You can send us your solution in an email attachment. Alternatively, you can
create a new repo with your Github account and send us the link.
**Please use a different repo name and do not fork this one.**

* Please do not perform any stress or load testing against our production
platform.
