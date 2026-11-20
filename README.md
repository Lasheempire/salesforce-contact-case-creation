# salesforce-contact-case-creation
Salesforce Screen Flow project that creates Cases from a Contact record while maintaining accurate record relationships.
# Contact-Based Case Creation Screen Flow

## Project Overview

Designed and built a Salesforce Screen Flow that allows users to create a Case directly from a Contact record page while automatically associating the Case with the correct Contact.

## Business Problem

Customer service representatives need an efficient way to create support Cases without accidentally associating them with the wrong Contact.

## Business Requirements

- Allow users to create Cases from the Contact Lightning Record Page.
- Automatically associate each Case with the current Contact.
- Prevent users from changing the Contact association within the Flow.
- Capture Subject, Description, Priority, Status, and Case Reason.
- Default Case Status to New.
- Display a confirmation after successful Case creation.
- Provide an error screen when Case creation fails.

## Salesforce Solution

Built a Screen Flow using Salesforce Flow Builder.

The Flow receives the current Contact record ID from the Lightning Record Page and maps it to the Case's ContactId field.

The Flow uses a Create Records element to save the Case, a fault path to handle creation errors, and a confirmation screen to notify users of successful completion.

## Salesforce Features Used

- Screen Flow
- Lightning App Builder
- Contact and Case standard objects
- Record ID variables
- Create Records element
- Fault handling
- Default field values

## Business Value

- Simplifies Case creation.
- Reduces incorrect Contact associations.
- Supports consistent data entry.
- Improves the user experience.
- Provides clear feedback when errors occur.

## Testing

Test scenarios include successful Case creation, correct Contact association, default Status assignment, and error handling.

## Project Type

Independent hands-on Salesforce Administrator portfolio project.
