# ERP setup, test plan and responsible-publication review

## Dependencies
- An authorized Dynamics 365 Finance & Operations development sandbox, supported compiler/build tools and permission to import X++ export packages.
- Appropriate model/package dependencies, test roles and non-production company data.
- Environment setup according to your organization's Dynamics release/support policy.

## Test checklist
1. Open and inspect each AXPP export in a compatible development tool.
2. Verify object names, models, classes, dependencies and references.
3. Compile before any execution; log warnings/errors.
4. For sales and purchase order customization, test validations and security roles using dummy orders.
5. For payment automation, **never run against real bank details, customer payments or production ledger entries during preliminary testing**.
6. Validate the reporting-related export with test records; confirm field mapping and SSRS deployment in sandbox.
7. Record environment version and evidence, then update README implementation status.

## Privacy and intellectual-property review
The functional-design PDF could contain organization-specific operations, names, commercial details or payment instructions. **Public GitHub is accessible to anyone**, even if a file is later removed from the latest commit, because history can retain it. Confirm you have permission to publish these materials. This review did not verify that the PDF is free of confidential content.

## Scope
These are export artifacts and documentation, not a fully reproducible ERP build. CI is static file inventory only.
