# ModelView Privacy Policy


**Effective date:** October 8, 2026


ModelView is a Windows application for locally converting, viewing, and reviewing engineering and 3D models. This policy explains how ModelView handles information when you use the application and its feedback and diagnostic services.


## Information processed locally


Model source files, converted assets, cached render data, preferences, and local work data are processed and stored on your Windows device. Successful conversion and viewing remain local. The failed-conversion diagnostic upload described below is an exception.


## Optional feedback and support


If you choose to use the in-app feedback or support feature, ModelView sends the content you submit and the information needed to operate that support conversation to the ModelView feedback service. This can include your message, conversation identifiers, timestamps, client or installation identifiers, and basic device or application status information. Please do not include confidential model files, passwords, or other sensitive information in feedback messages.


We use this information to deliver the feedback feature, respond to requests, maintain service reliability and security, and diagnose application issues.


## Automatic error diagnostics and failed model samples

When an error occurs, ModelView automatically sends bounded diagnostic information to the ModelView feedback service to reproduce errors and fix bugs. This can include installation identifiers, application and converter versions, Windows and basic hardware information, source format and size, failure stages, attempt history, timestamps, exit codes, memory measurements, and error logs. Diagnostic text is redacted and limited in length, but a model sample itself can contain confidential design information.

If model conversion fails and the original source file is readable, unchanged, non-empty, and smaller than 1 MiB (1,048,576 bytes), ModelView compresses that original file with gzip and uploads it with the diagnostic report. This size limit applies before compression. Larger models are not attached. Model file names and original paths are not attachment metadata. The service validates the file size and SHA-256 and stores the restored original file for authorized administrators to download for debugging. Samples are not published.

Automatic diagnostics do not require starting a feedback conversation. If delivery fails, a bounded local queue can retain compressed reports and retry later. Do not process confidential models with ModelView if this automatic failure reporting does not meet your requirements. You can request deletion of diagnostic reports and model samples through the contact below; do not post models or confidential details in a public issue.

## Updates and Microsoft Store


The Microsoft Store version is updated through Microsoft Store. Microsoft may process information under its own privacy statement when it provides Store services. ModelView does not include advertising or in-app purchases.


## Sharing


We do not sell personal information or use it for targeted advertising. We disclose information only to operate the feedback and diagnostic services, to comply with applicable law, or to protect the security and integrity of ModelView and its users.


## Retention and security


Locally processed model data remains under your control on your device. Feedback records, diagnostics, and failed model samples are retained only for as long as reasonably needed to operate and improve support, resolve issues, meet legal obligations, or protect the service. We use reasonable safeguards appropriate to the nature of the information.


## Your choices and requests


You can avoid sending optional feedback by not using the feedback feature. Automatic error reporting operates separately as described above. You can remove local ModelView data using Windows and file system controls. For a privacy request or question, open an issue at https://github.com/GoodLuckIce/modelView/issues. Do not include sensitive information in a public issue.


## Changes


We may update this policy when ModelView changes. We will publish the current version at this URL and update the effective date.

