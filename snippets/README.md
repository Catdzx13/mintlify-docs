# CrizonShop rich-content snippets

These snippets adapt useful documentation patterns—card grids, steppers, expandable details, and tabs—to Mintlify's native MDX components. They are original project templates and do not copy GitBook renderer source code.

Import a snippet from a page, then pass localized text as props:

```mdx
import PolicyOverview from "/snippets/ui/policy-overview.mdx";

<PolicyOverview
  firstTitle="Delivery"
  firstText="Usually completed within 15 minutes to 6 hours."
  secondTitle="Warranty"
  secondText="Covered faults are reviewed using order evidence."
  thirdTitle="Support"
  thirdText="Contact contact@crizonshop.com."
/>
```

## Available patterns

- `policy-overview.mdx`: three-card summary for the top of an article.
- `decision-cards.mdx`: side-by-side covered/not-covered outcomes.
- `process-steps.mdx`: four-step operational or support flow.
- `comparison-tabs.mdx`: three switchable cases, markets, or audiences.
- `faq-accordion.mdx`: three optional details or frequently asked questions.
- `evidence-panel.mdx`: source, verification time, and evidence reminder.

Use no more components than the content needs. Material limitations, prices, refund conditions, and user obligations must remain visible without requiring an accordion to be opened.
