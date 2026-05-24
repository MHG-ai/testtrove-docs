# AI Features

TestTrove includes AI-assisted workflows for release planning, test case generation, test case repair, release overview, and project context.

## AI Context

AI Context stores project-specific context that improves AI-generated outputs.

Use AI Context to add:

- Product behavior
- Testing rules
- Domain terminology
- Business constraints
- Project-specific expectations

Good AI context examples:

- Login requires MFA for admin users.
- Payment failures must show retry guidance.
- Regression cases must include Chrome and Firefox coverage.
- Critical workflows require high-priority test cases.

## AI Release Insights

AI release insights are generated from release scope.

### Generate AI Release Insights

1. Open a project.
2. Go to Releases.
3. Select Add Release.
4. Enter release details.
5. Upload a release scope document.
6. Check Generate Plans (AI).
7. Select Save.

When AI insights are generated, the AI Release Insights panel displays:

- Overview
- Test Cases
- Release Plan
- Risks
- Quality Gates
- Metrics
- Coverage Intelligence

## AI Test Case Creation From Release Insights

In the Test Cases tab:

1. Review the AI generated cases.
2. Select one or more cases using the checkbox beside each case.
3. Select Create Selected Cases.

For a single case, select Accept & Create.

TestTrove checks whether the target folder already exists. If the folder does not exist, TestTrove creates it first, then creates the test case. Bulk creation is used when saving selected AI cases.

To modify a suggested case before creating it:

1. Select Edit.
2. Update the case fields.
3. Select Accept & Create.

## AI Release Plan Creation

1. In AI Release Insights, select Create Release Plan.
2. Review the AI plan suggestions in the Review AI Test Plans modal.
3. Select only the plans you want to create.
4. Edit plan details such as Plan Name, Test Point, Scope, and Description.
5. Confirm Create Selected Plans.

The current user is used as the plan assignee.

## AI Generate Test Cases From Folder Context

From the TestCases page, AI generation can be used for a selected folder. Generated cases can be reviewed, selected, and saved in bulk.

## AI Test Case Repair

AI repair compares the existing test case with suggested improvements.

1. Review the old and new values.
2. Regenerate if needed.
3. Save the changes if they are acceptable.

## Best Practices

- Add AI Context before generating AI cases or release plans.
- Upload clear release scope documents.
- Review AI-generated content before creating records.
- Select only the AI plans and cases that match release scope.
- Keep folder names meaningful so AI-created cases are organized well.

