# CS 1632 Midterm 1 Exam Study Guide - Spring 2021

The midterm is going to be open book but individual work.  I will not take any
questions during the midterm about the material that we learned, just like any
exam.  The exam will be released on GradeScope on the date of the exam.  Please
try solving the "Sample Exam (Ungraded)" to practice the mechanics of taking an
exam on GradeScope.

The midterm will cover everything up to Writing Testable Code.  I recommend you
review the slides and the textbook (See syllabus.md for which chapters are
required reading.  The reading is also on the last slide of each lecture).
Going over the TopHat questions will be quite helpful too.  You are also
expected to have completed Exercises 1, 2, and Supplement 1, and be able to
answer related questions.

The exam will consist of these types of questions:
  * Multiple choice questions
  * Fill in the blank questions
  * Short answer questions (explain a concept, discuss pros/cons, etc.)
  * JUnit / Gherkin / Cucumber code tracing questions
  * JUnit / Gherkin / Cucumber coding questions

If you want more practice with Gherkin + Cucumber, try this out:
https://github.com/wonsunahn/CS1632_Fall2020/blob/master/sample_code/cucumber_example/

You may get a similar question on the exam, asking you to translate JUnit to Gherkin + Cucumber.

Here are the key topics to study in preparation for the test.

## TESTING THEORY AND TERMINOLOGY
* Be able to explain why exhaustive testing is virtually impossible, even with just one method.
* Be able to perform equivalence class partitioning given a set of requirements.
* Be able to come up with boundary and interior values given a test scenario.
* Be able to differentiate between base, edge, and corner cases.
* Be able to explain the difference between static vs dynamic testing and give examples of each.
* Be able to explain the difference between black box / white box / gray box testing and give examples of each.
* Be able to define all terminology introduced or fill in the blank.

## REQUIREMENTS ANALYSIS
* Be able to argue why requirements should not specify implementation.
* Be able to clearly define the difference between requirements verification and requirements validation.
* Be ready to give a few examples of checks performed during requirements validation and what they mean
  * validity, completeness, consistency, realism, ambiguity, verifiability
* Be able to differentiate between Functional Requirements vs Non-Functional Requirements (Quality Attributes)
* Be able to define all terminology introduced or fill in the blank.

## TEST PLANS
* Be able to give examples of preconditions and postconditions.
* Be able to explain what a regression test is and why it is important.
* Be able to explain what problems in a test case may cause it to become not reproducible.
* Be able to explain what problems in a test case cause it to not be independent.
* Be able to explain the hierarchy of test cases, test plans, test suites.
* Be able to write a traceability matrix given requirements and test cases
  * Be able to tell problems with a test plan based on the traceability matrix
* Be able to critique an example test case on what problems it may have.
  * Problems with preciseness, reproducibility, independence.
* Be able to define all terminology introduced or fill in the blank.

## DEFECT REPORTING
* Be able to explain the difference between a defect and a candidate for enhancement.
* Be able to explain the difference between explicit and implicit requirements.
* Be able to explain why implicit requirements make it sometimes hard to tell whether something is a defect or an enhancement.
* Be able to explain why sometimes software is released with known bugs inside them.
* Be able to explain why bad coding style is not a defect.
* Be able to explain what triage and sub-triage are.
* Be able to critique an example defect report on what problems it may have.
  * Problems with preciseness and reproducibility.
* Be able to define all terminology introduced or fill in the blank.

## BREAKING SOFTWARE
* Given buggy code, be able to recognize what the problem is and be able to categorize it.
  * Logic errors
  * Null pointer errors
  * Floating point / Rounding errors
  * Integration errors
  * Missing data errors
  * Bad data errors
  * Display errors
  * I/O errors
  * Configuration errors

## AUTOMATED TESTING
* Be able to discuss in-depth of the pros and cons of automated testing.
  * Why automated testing can be brittle and narrow.
* Be able to explain what test automation looks like in a blackbox testing context and a whitebox testing context.

## UNIT TESTING
* Be able to list the 4 levels of testing in a hierarchy: acceptance/system/integration/unit.
* Be prepared to write some unit tests in JUnit.
  * Names of JUnit methods will be provided, but you should know _how_ to use them.
* Be prepared to write JUnit code for stubs, test doubles, mocks, and behavior verification.
* Testing private methods
  * You will NOT be asked to write code to test them using reflection.
  * You may be asked to discuss why/why not one might not decide to test them.

## TDD
* Be able to draw the red-green-refactor loop.
  * Be able to explain each of its components.
* Be able to explain principles of TDD (including explaining acronyms):
  * YAGNI
  * KISS
  * "Fake it 'til you make it"
  * Avoid interdependency
  * Avoid slow tests
* Be able to discuss the benefits and drawbacks of TDD.
  * When to use it?
  * When not to use it?

## BDD
* Be able to discuss two problems in TDD that BDD solves.
  * Hard to get feedback about requirements from stakeholders
  * Hard to change requirements mid-development due to tests breaking
* Be able to discuss drawbacks of BDD.
  * Drawbacks of specification by example
* Be able to take Gherkin and Cucumber code and trace through it and explain the end result.

## WRITING TESTABLE CODE
* Be able to explain basic strategies for testable code.
  * Segment code - make it modular
  * The DRY Principle
  * Give yourself something to test
  * TUFs and TUCs
  * Make it easy to satisfy preconditions
  * Make it easy to reproduce
  * Make it easy to localize
* Be able to perform dependency injection for localization or reproducibility (See TopHat questions).
* Be able to describe two strategies for dealing with legacy code.
  * Pinning tests
  * Seams

