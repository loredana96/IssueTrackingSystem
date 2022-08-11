# IssueTrackingSystem
In this repo I will build a system for managing and tracking issues. I will use Angular reactive forms for reporting new issues. I will also use **Clarity Design System** from VMware for designing the foms and desplaying the issues. 
The following topics will be covered in this app:
* Installing Clarity Design System to an Angular application
* Displaying an overview of issues
* Reporting new issues
* Making an issue as resolved
* Turning on suggestions for new issues

## Essential background theory
  ### Template-driven forms
   * They are easy and straightforward to set up in an Angular application. 
   * Used mostly for basic application where simple validation is needed and it only has a fiew fields
   * Template-driven forms do not scale well and are difficult to test because they are defined in the template of the component

  ### Reactive forms
  * They are based on a reactive programming approach
  * Handle cases where complexity increases Ex: enterprise applications
  * Tenth of fields, a lot of validation, large forms, these are all good reasons for using Modal Driven Forms
  * Modern functionality like auto-save, undo-redo can be added and handled much easier
  * Complex interfield validations are handled much easier with reactive forms
  * Reactive forms operate in the TypeScript class of the component, and they are easier to test and scale better than template-driven forms
