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

