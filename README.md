# Microsoft Dynamics 365 Finance & Operations | ERP Development Samples

A portfolio collection of **Dynamics 365 Finance & Operations / X++ artifacts**, including a runnable class export, a reporting-related export, sales/purchase order customization material and a functional design PDF.

This is an **independent learning/portfolio repository**. It is **not an official Microsoft sample, certified Microsoft solution, deployed ERP extension or verified production automation**.

## Repository contents

| Location | Artifact |
|---|---|
| [xpp/Bangladesh_RunableClass.axpp](xpp/Bangladesh_RunableClass.axpp) | Runnable class export |
| [xpp/KOR-SSRS-Report.axpp](xpp/KOR-SSRS-Report.axpp) | SSRS-report-related export |
| [xpp/SO & PO Customization.axpp](xpp/SO%20%26%20PO%20Customization.axpp) | Sales and purchase order customization export |
| [docs/Bangladesh_Payment_Automation_Functional_Design.pdf](docs/Bangladesh_Payment_Automation_Functional_Design.pdf) | Functional design reference |
| [docs/SETUP_AND_REVIEW.md](docs/SETUP_AND_REVIEW.md) | Import prerequisites, test plan and public-sharing review |

## Technology and scope

- **Microsoft Dynamics 365 Finance & Operations** development environment
- X++ artifact import through supported tools in an appropriate F&O development sandbox
- SSRS reporting concepts and sales/purchase order customization
- Functional requirement and design handover

The `.axpp` files are **binary export artifacts**, not standalone SQL scripts or a Node/Python application. They need a compatible F&O environment and should not be interpreted as runnable outside that system.

## How to review

1. Read [setup and review instructions](docs/SETUP_AND_REVIEW.md).
2. Inspect the PDF for confidentiality, customer identifiers and organizational information before continuing public distribution.
3. Import the individual `.axpp` artifacts only into an authorized, isolated development environment.
4. Inspect dependencies and compile each item; run unit and UAT scenarios with synthetic test data.
5. Document the outcome before claiming successful deployment or automation.

## Validation and limitations

GitHub Actions checks only that tracked artifacts exist and are nonempty. It **cannot compile X++, import an AOT model, run SSRS, or test Finance & Operations business workflows**. The functional PDF and exports have not been runtime inspected by this process; avoid presenting them as certified production-ready.

The project is maintained independently by [bhagabatabrahma0106-dotcom](https://github.com/bhagabatabrahma0106-dotcom).
