# ContextQA lab — Salesforce · Visualforce → LWC

Educational source fork of [trailheadapps/visualforce-to-lwc](https://github.com/trailheadapps/visualforce-to-lwc). Original history, notices and license are retained. This is not an endorsed integration or a customer production app.

**Status: source and exercises available. Public deployment, platform import and ContextQA run results are not verified.**

Starting source commit: `81001b70214843d1c10546b1a4c26a30c0412d1f`.

## Setup and scope

Use an authorized Salesforce org. Select one of the actual paired Visualforce/LWC patterns in the source before recording. A Visualforce example is not blanket Salesforce Classic coverage; Classic needs its own enabled environment.

Follow the [original setup instructions](../README.md#upstream-project-documentation). See [stack/platform guidance](https://github.com/contextqaai/testing-lab/blob/main/PLATFORMS.md) for deployment boundaries.

## Exercises

| Scenario | Explicit assertion |
|---|---|
| Select pair | The selected Visualforce example and its LWC equivalent both load. |
| Same input | Equivalent fixture input is entered on both implementations. |
| Same output | The expected business result is consistent across the pair. |
| Validation parity | The chosen invalid input produces the specified feedback on both. |
| Migration regression | A disclosed change in one isolated variant is detected by the same business assertion. |

These are acceptance exercises, not claims that upstream currently satisfies each desired requirement. Inspect the implemented workflow and fixtures before generating executable steps. Missing validation/auth may deliberately demonstrate a failure and must be disclosed.

## End-to-end lesson

Start an owned/authorized copy with synthetic fixtures. State the assertion, create/review a test in your authenticated ContextQA workspace, execute, and inspect the actual verdict. Introduce one disclosed regression in a separate variant, rerun the same assertion, fix the app and rerun. Confirm mutations against disposable data. Keep credentials and private reports out of this repository.

Record app commit/build, fixture/scenario version, browser/runner version, environment and timestamp with every real report. A cached report is recorded evidence, not a new run. No ContextQA report has been generated for this fork yet.

[ContextQA setup](https://contextqa.com/tutorials/getting-started-with-contextqa-test-automation/) · [Central catalog](https://github.com/contextqaai/testing-lab)
