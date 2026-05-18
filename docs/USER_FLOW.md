# User Flow

## Primary User

Local service businesses

## Primary Flow

1. Customer sends a WhatsApp message to the business.
2. Webhook verifies the message and routes it to the AI workflow.
3. The agent answers FAQs, qualifies intent, and detects booking needs.
4. Sensitive or high-value conversations are escalated to a human.

## Happy Path Outcome

The user receives a clear business result from Lead.AI WhatsApp Agent without needing to understand the underlying AI or infrastructure.

## Failure And Handoff Paths

- If required data is missing, ask for the minimum additional information.
- If the AI output is uncertain, show a limitation or request human review.
- If an integration fails, preserve the input and show a recoverable error.
- If private data is involved, avoid exposing it in logs or public examples.

## Demo Requirements

- Use safe sample data.
- Show the main workflow end to end.
- Include one screenshot or short video after implementation.
