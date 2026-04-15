# Prompt Anatomy

General structure of an effective prompt.

| Component                  | Description                                                                                                                |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| **Persona**                | The role the model should play                                                                                             |
| **Instructions**           | Core of the prompt — what you're asking the model to do. Should be clear, concise, and typically start with an action word |
| **Input content**          | Additional input for the model to process (text, images, etc.)                                                             |
| **Format**                 | Output requirements (paragraph, bullet points, document, JSON, etc.)                                                       |
| **Additional information** | Context, background knowledge, constraints, etc. to help the model generate a better response                              |

> These components are optional and you can alter their order, but the prompt should at least have **instructions**.

---

## Example

> _As a Software Engineer preparing documentation for a project (**Persona**) generate a step by step guide (**Instructions**) on how to use the `/project` API endpoint (**Input content**), written in Markdown, including clear descriptions and example calls (**Format**). Assume the audience is familiar with REST APIs but not this particular endpoint. Avoid too much technical jargon where possible (**Additional information**)._
