# Private/Internal Repository Reasoning Record (PIRR)
<!-- This template provides a structured format for documenting the rationale behind the requirement for a private or internal repository, ensuring that the decision-making process is transparent and well-documented. -->

## Repository Name
<!-- Specify the name of the repository for which this PIRR is being created -->
gcp-cloudbuild-ci-module

## Date Reviewed
<!-- Specify the date when this PIRR was last reviewed in yyyy-mm-dd format -->
2025-11-19

## Reason for Private/Internal Repository
<!-- Clearly state the specific reasons or requirements necessitating the use of a private or internal repository for this project -->
This repo will contain sensitive terraform configuration that is not appropriate for public consumption, but will need to be viewed by internal collaborators.

## Sensitivity of Information
<!-- Describe the sensitivity of the information contained in the repository and why it requires restricted access -->
This will contain detailed information about the permissions allocated to centralised service accounts that control a number of projects

## Access Control Needs
<!-- Explain the specific access control needs or restrictions that justify the use of a private or internal repository -->
This repo should be accessible to internal colleagues, for reference and the sharing of best practice. But Unavailable to the general public.

## Collaboration Requirements
<!-- Outline any collaboration requirements that are better addressed through a private or internal repository as opposed to a public one -->
This would allow us to store information directly in the repo, rather than needing to abstract them to secrets, making the codebase more usable.

## Security and Compliance Considerations
<!-- Address any security or compliance considerations that influence the decision to use a private or internal repository -->
Already mentioned above.

## Additional Notes
<!-- Include any additional context, considerations, or relevant details pertaining to the need for a private or internal repository -->
N/A
