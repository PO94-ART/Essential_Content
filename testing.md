## Navigation testing

| Starting page | Link tested                | Expected page                                       |      |      |

| Home          | About                      | About page                                          |Pass  | None |
| Home          | Activities                 | Activities page                                     | Pass | None |
| About         | Contact                    | Contact page                                        | Pass | None |
| Activities    | Home                       | Home page                                           | Pass | None |
| Contact       | About                      | About page                                          | Pass | None |
| Home          | Activities link in content | Activities page                                     | Pass | None |
| Home          | Contact link in content    | Contact page                                        | Pass | None |
| Contact       | Email link                 | Email application opens                             | Pass | None |
| All pages     | Navigation links using Tab | Links can be reached and selected using the Tab key | Pass | None |
| All pages     | Contextual links using Tab | Links can be reached and selected using the Tab key | Pass | None |


## Navigation testing class 2

| Test                | Expected result                          | Actual result    | Correction          | Retest |

| Home link           | Opens homepage                           | Passed           | None                | Passed |
| About link          | Opens About page                         | Passed           | None                | Passed |
| Activities link     | Opens Activities page                    | Failed initially | Corrected link path | Passed |
| Contact link        | Opens Contact page                       | Passed           | None                | Passed |
| Images              | All images load                          | Passed           | None                | Passed |
| Keyboard navigation | Links can be selected with Tab and Enter | Passed           | Added focus style   | Passed |


## Navigation testing class 3


| Test                            | Expected result                                 | Actual result                                            | Pass or fail | Correction and retest |

| Select each form label          | The associated control receives focus           | The correct form control receives focus                  | Pass         | No correction needed |
| Select preferred contact method | Only one radio button can be selected           | Only one radio button can be selected at a time          | Pass         | No correction needed |
| Open enquiry-type menu          | All enquiry options are available               | All five enquiry options are available                   | Pass         | No correction needed |
| Use the Tab key                 | Focus moves through controls in a logical order | Focus moves through the form controls in a logical order | Pass         | No correction needed |



## Navigation testing class 4 
## Enquiry Form Testing

| Test | Test data or action | Expected result | Actual result | Pass or fail | Correction and retest |

| Empty form             | Submit without entering anything                    | Submission is stopped at the first required field        | The browser stopped the form and requested the required field | Pass | No correction needed |
| Invalid email          | Enter `student@`                                    | Browser requests a valid email address                   | The browser requested a valid email address                   | Pass | No correction needed |
| No enquiry type        | Leave the instructional option selected             | Browser requests a genuine selection                     | The browser requested an enquiry type                         | Pass | No correction needed |
| Visitor count too low  | Enter `0`                                           | Submission is stopped                                    | The browser rejected the value                                | Pass | No correction needed |
| Visitor count too high | Enter `21`                                          | Submission is stopped                                    | The browser rejected the value                                | Pass | No correction needed |
| Short message          | Enter fewer than 20 characters                      | Submission is stopped                                    | The browser requested at least 20 characters                  | Pass | No correction needed |
| No contact method      | Leave all radio buttons unselected                  | Browser requests one option                              | The browser requested a contact method                        | Pass | No correction needed |
| No contact agreement   | Leave the consent checkbox unselected               | Submission is stopped                                    | The browser requested the checkbox to be selected             | Pass | No correction needed |
| Valid form             | Complete all required fields with valid information | Form accepts the entries                                 | The form accepted all valid entries                           | Pass | No correction needed |
| Keyboard operation     | Complete the form without using a mouse             | Every control is reachable, usable and has visible focus | All controls were reachable and focus was clearly visible     | Pass | No correction needed |

