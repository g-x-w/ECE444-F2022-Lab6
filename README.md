# ECE444-F2022-Lab6

## Group Project Test Cases

https://github.com/ECE444-2022Fall/project-1-web-application-design-education-pathways-group-8-8ball/blob/main/Education_Pathways/tests/test_app.py#L149-L172

Test cases I wrote:
- test_filter_by_course_code()
- test_filter_by_course_dept()
- test_search_by_keyword()

## TDD Pros & Cons

### Pros
- high code test coverage
- encourages modular code architecture
- improves PR standardization and efficiency by clearly demonstrating passing and failing test cases
- improves workflow by automating time-consuming manual tests

### Cons
- time spent writing test code could have been spent writing actual feature code
- slows down development because of need for consistent thorough unit tests
- unit tests don't emulate or replicate all the weird ways actual users might use features
- unit tests could pass but users could still experience novel errors uncaught by automated testing 