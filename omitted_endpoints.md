## Omitted Endpoints

The following endpoints are not included in the client libraries.

You can use these API endpoints from your application by making your own API calls to docusign.net.

| HTTP Method | Endpoint |
| --- | --- |
| POST | {vx}/accounts |
| DELETE | {vx}/accounts/{accountId} |
| GET | {vx}/accounts/{accountId}/billing_charges |
| GET | {vx}/accounts/{accountId}/billing_invoices |
| GET | {vx}/accounts/{accountId}/billing_invoices_past_due |
| GET | {vx}/accounts/{accountId}/billing_invoices/{invoiceId} |
| GET | {vx}/accounts/{accountId}/billing_payments |
| POST | {vx}/accounts/{accountId}/billing_payments |
| GET | {vx}/accounts/{accountId}/billing_payments/{paymentId} |
| GET | {vx}/accounts/{accountId}/billing_plan |
| PUT | {vx}/accounts/{accountId}/billing_plan |
| PUT | {vx}/accounts/{accountId}/billing_plan/purchased_envelopes |
| DELETE | {vx}/accounts/{accountId}/brands |
| GET | {vx}/accounts/{accountId}/brands |
| POST | {vx}/accounts/{accountId}/brands |
| GET | {vx}/accounts/{accountId}/bulk_envelopes |
| GET | {vx}/accounts/{accountId}/bulk_envelopes/{batchId} |
| GET | {vx}/accounts/{accountId}/connect |
| POST | {vx}/accounts/{accountId}/connect |
| PUT | {vx}/accounts/{accountId}/connect |
| DELETE | {vx}/accounts/{accountId}/connect |
| GET | {vx}/accounts/{accountId}/connect/{connectId} |
| POST | {vx}/accounts/{accountId}/connect/{connectId} |
| PUT | {vx}/accounts/{accountId}/connect/{connectId} |
| DELETE | {vx}/accounts/{accountId}/connect/{connectId} |
| DELETE | {vx}/accounts/{accountId}/connect/mobile_notifiers |
| GET | {vx}/accounts/{accountId}/connect/mobile_notifiers |
| PUT | {vx}/accounts/{accountId}/connect/mobile_notifiers |
| GET | {vx}/accounts/{accountId}/consumer_disclosure |
| GET | {vx}/accounts/{accountId}/consumer_disclosure/{langCode} |
| DELETE | {vx}/accounts/{accountId}/envelopes/{envelopeId}/recipients/{recipientId}/bulk_recipients |
| GET | {vx}/accounts/{accountId}/envelopes/{envelopeId}/recipients/{recipientId}/bulk_recipients |
| PUT | {vx}/accounts/{accountId}/envelopes/{envelopeId}/recipients/{recipientId}/bulk_recipients |
| GET | {vx}/accounts/{accountId}/envelopes/{envelopeId}/recipients/{recipientId}/consumer_disclosure |
| GET | {vx}/accounts/{accountId}/envelopes/{envelopeId}/recipients/{recipientId}/consumer_disclosure/{langCode} |
| DELETE | {vx}/accounts/{accountId}/groups/{groupId}/brands |
| GET | {vx}/accounts/{accountId}/groups/{groupId}/brands |
| PUT | {vx}/accounts/{accountId}/groups/{groupId}/brands |
| GET | {vx}/accounts/{accountId}/templates/{templateId}/documents/{documentId}/pages/{pageNumber}/page_image |
| DELETE | {vx}/accounts/{accountId}/templates/{templateId}/recipients/{recipientId}/bulk_recipients |
| GET | {vx}/accounts/{accountId}/templates/{templateId}/recipients/{recipientId}/bulk_recipients |
| PUT | {vx}/accounts/{accountId}/templates/{templateId}/recipients/{recipientId}/bulk_recipients |
| DELETE | {vx}/accounts/{accountId}/users/{userId}/cloud_storage |
| GET | {vx}/accounts/{accountId}/users/{userId}/cloud_storage |
| POST | {vx}/accounts/{accountId}/users/{userId}/cloud_storage |
| DELETE | {vx}/accounts/{accountId}/users/{userId}/cloud_storage/{serviceId} |
| GET | {vx}/accounts/{accountId}/users/{userId}/cloud_storage/{serviceId} |
| GET | {vx}/accounts/{accountId}/users/{userId}/cloud_storage/{serviceId}/folders |
| GET | {vx}/accounts/{accountId}/users/{userId}/cloud_storage/{serviceId}/folders/{folderId} |
| GET | {vx}/accounts/provisioning |
| GET | {vx}/billing_plans |
| GET | {vx}/billing_plans/{billingPlanId} |