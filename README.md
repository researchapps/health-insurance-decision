# Health Insurance Decision

> Should We Be on the Same Health Care Plan?

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/researchapps/health-insurance-decision/master?filepath=health_insurance.ipynb)

One of our employers recently removed a health care plan option, leaving us (two domestic partners) to decide if it would be better to retain separate plans, or to have one of us join the other's.  Instead of focusing
on what was lost (the plan no longer available) I decided to focus on the options that I did have -
choosing a different plan offered by the employer, or joining my partner's. I also
carefully walked through some terms that weren't clear to me, and generated plots
and some basic thoughts about them. You might need to customize this for your use case,
but hopefully it can be a programmatic start to figuring out your options.

 - [health insurance notebook](health_insurance.ipynb)

For some basic background, the plans are similar in that they both offer a health savings account (HSA), and then have a relatively reasonable monthly premium, along with a maximum out of pocket. As you might guess, when you add a second party to a single person's plan, the out of pocket maximum increases appropriately, the deductible doubles, and the monthly premium also increases.

Some caveats - this breakdown is specific to two similar plans offered by specific individual employers (not stated). As you read this, keep in mind that some expenses are covered at differenet rates (for example, preventative might be covered at 100%), that the calculation doesn't take into account tax benefits from HSA, and that there's other tax implications of being on the same plan as domestic partners that weren't covered here.
