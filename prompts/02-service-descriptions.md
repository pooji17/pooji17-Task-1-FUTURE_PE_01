# Prompt 2 — Service Descriptions

## Purpose
Generates individual service descriptions for the services page, including inclusions and differentiation.

---

## Prompt

```
Write a service description for [SERVICE_NAME] offered by [BUSINESS_NAME].

Structure:
- Service name (as written on menu/brochure)
- 2–3 sentence description focused on the customer's experience, not features
- A bullet list of 4–5 inclusions
- One sentence on why this business does it better than alternatives

Tone: [TONE]. Target customer: [CUSTOMER PROFILE].
Avoid: pricing, technical jargon, superlatives without evidence.
```

---

## Brewed Horizons Services — Variable Sets

### Service 1: Specialty Coffee Bar
| Variable | Value |
|---|---|
| SERVICE_NAME | Specialty Coffee Bar |
| BUSINESS_NAME | Brewed Horizons Cafe |
| TONE | friendly |
| CUSTOMER PROFILE | coffee enthusiasts aged 22–40 who can tell the difference between a flat white and a latte |

### Service 2: All-Day Brunch
| Variable | Value |
|---|---|
| SERVICE_NAME | All-Day Brunch |
| CUSTOMER PROFILE | young professionals and families looking for weekend brunch that doesn't rush them |

### Service 3: Private Events & Buyouts
| Variable | Value |
|---|---|
| SERVICE_NAME | Private Events & Buyouts |
| CUSTOMER PROFILE | HR managers, birthday planners, and creative agencies looking for a non-hotel venue |

### Service 4: Work-Friendly Daytime Space
| Variable | Value |
|---|---|
| SERVICE_NAME | Work-Friendly Daytime Space |
| CUSTOMER PROFILE | freelancers, remote workers, and startup founders who work better outside the home |

---

## Batch prompt (run all 4 at once)

```
You are a professional website copywriter for Brewed Horizons Cafe, a specialty coffee café 
and all-day brunch spot in Banjara Hills, Hyderabad.

Write service descriptions for all 4 of the following services. For each, provide:
- Service name
- 2–3 sentence customer-experience description
- 4–5 bullet inclusions
- 1 sentence on differentiation

Services: Specialty Coffee Bar, All-Day Brunch, Private Events & Buyouts, 
Work-Friendly Daytime Space.

Tone: friendly and warm. Avoid pricing and generic superlatives.
```
