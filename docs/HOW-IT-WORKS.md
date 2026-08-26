# How Understand Onboard Works

Generate an evidence-backed onboarding guide from a repository and its operational surfaces.

![Detailed systems blueprint for Understand Onboard](../assets/system-blueprint.png)

## Stages

### 1. Identify entry points and ownership areas

**Primary surface:** `Repository map`

Record the input, operation, observable output, and any decision that changes scope. Stop here if the output is missing, contradictory, or insufficient for the next stage.
### 2. Map build test and deployment paths

**Primary surface:** `Runtime surfaces`

Record the input, operation, observable output, and any decision that changes scope. Stop here if the output is missing, contradictory, or insufficient for the next stage.
### 3. Extract domain vocabulary from code

**Primary surface:** `Domain concepts`

Record the input, operation, observable output, and any decision that changes scope. Stop here if the output is missing, contradictory, or insufficient for the next stage.
### 4. Trace one end-to-end user flow

**Primary surface:** `Operational workflows`

Record the input, operation, observable output, and any decision that changes scope. Stop here if the output is missing, contradictory, or insufficient for the next stage.
### 5. Document common failure surfaces

**Primary surface:** `Onboarding guide`

Record the input, operation, observable output, and any decision that changes scope. Stop here if the output is missing, contradictory, or insufficient for the next stage.
### 6. Assemble a role-aware onboarding path

**Primary surface:** `Onboarding guide`

Record the input, operation, observable output, and any decision that changes scope. Stop here if the output is missing, contradictory, or insufficient for the next stage.

## Failure handling

- **Authorization failure:** do not probe credentials or broaden access; report the missing authority.
- **Target ambiguity:** stop before mutation and request the minimum identifying information.
- **Tool or service failure:** retain error evidence, retry only safe transient failures, and cap retries.
- **Verification failure:** classify the run as incomplete even when the preceding operation returned success.

## Completion evidence

The handoff should contain the original request, inspection state, preview or plan, exact execution result, direct verification, and a final receipt naming limitations and withheld actions.
