# Lab 2: Encapsulation and Properties

## Description
This iteration refactors the `Planet` class to strictly enforce Encapsulation principles. Validation logic has been moved from the main program into class Properties to ensure data integrity at the object level.

## Objectives
* Replace direct field access with Properties.
* Implement validation logic within `set` accessors.
* Utilize private helper methods to hide implementation details.

## Key Changes
* **Full Encapsulation:** All class fields are now `private`.
* **Properties:** Public properties are used for all data access.
* **Validation:** `set` accessors now include conditional logic to reject invalid data.
* **Advanced Features:**
    * Auto-properties with default values.
    * Calculated properties (derived from other data).
    * Asymmetric accessor levels (different scope for `get` and `set`).
