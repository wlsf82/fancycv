# fancycv
```
// This is just an experiment of creating a CV using jasmine syntax (Work In Progress).

describe("Walmyr Filho's cv", () => {
    beforeAll("Contacts", () => {
        const email = "wlsf82@gmail.com";
        const mobile = "+47 469 39 756";
        const aboutMe = "https://about.me/walmyr-filho";
        const medium = "https://medium.com/@walmyrlimaesilv;
    });

    describe("Education", () => {
        const education = {
            university: "PUCRS",
            title: "Bachelor in business management with emphasis in system information analysis",
            year: 2012
        };
    });

    describe("Professional experience", () => {
        it("should verify you current role base on your current, previous and older job", () => {
            const jobs = {
                current: {
                    company: "appear.in",
                    role: "QA engineer",
                    mainActivities: [
                        "e2e test automation with Protractor",
                        "UI test automation with XCUITest",
                        "CI/CD infrastructure and system management",
                        "code review"
                    ],
                    stack: [ "node.js", "protractor", "selenium webdriver js", "tape", "XCUITest", "Terraform", "GoCD" ]
                },
                previous: {
                    company: "taller.net.br",
                    role: "QA engineer",
                    mainActivities: [
                        "e2e test automation with Protractor and Cucumber",
                        "CMS development with Drupal framework"
                    ],
                    stack: [ "node.js", "protractor", "cucumber", "Drupal", "HTML", "CSS", "javascript", "SASS", "Vagrant" ]
                },
                older: {
                    company: "adp.com",
                    role: "Senior QA analyst",
                    mainActivities: [
                        "e2e test automation with Selenium and HT QTP",
                        "bug tracking management",
                        "performance testing analysis"
                    ],
                    stack: [ "java", "VBScript", "SQL" ]
                }
            };

            expect(jobs.current.role).toEqual("QA engineer");
        });
    });

    describe("Other projects and comunity contribution", {

    });
});
```
