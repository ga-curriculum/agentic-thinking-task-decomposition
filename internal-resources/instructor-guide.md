<h1>
  <span class="headline">Agentic Thinking & Task Decomposition</span>
  <span class="subhead">Instructor Guide</span>
</h1>

## Module Overview

This 90-minute module teaches students how to systematically decompose ambiguous business goals into precise, machine-executable tasks. The focus is on eliminating ambiguity—the primary cause of AI agent failure—through structured frameworks and multi-agent patterns.

## Session Structure

### Opening (5 minutes) - Interactive Exercise
** Start with Impact:** Begin immediately with the interactive exercise in microlesson-01:

> Present learners with: "Find out why our new feature is underperforming and suggest what to do about it."
> 
> Ask them to write down the first three questions they would ask to clarify the task.

**Key Teaching Moment:** Use their responses to illustrate the inherent ambiguity. Most responses will reveal the need for clarification, leading naturally into the necessity of task decomposition.

### Concepts (15 minutes)
- **Focus:** Ambiguity as the enemy, not difficulty
- **Key Message:** Clear examples of vague vs. decomposed requests
- **Teaching Tip:** Use concrete business examples from students' domains when possible

### Microlesson 1: Framework & Practice (45 minutes)
**Part 1: 4-Step Framework (15 minutes)**
- Goal → Sub-tasks → Tools → Checks
- Emphasize the trade-off between granularity and latency

**Part 2: Micro-Lab (8 minutes)**
- Monitor student progress on the competitor analysis task
- Review 2-3 examples in chat, highlighting good decomposition practices
- **Common Mistakes to Address:**
  - Tasks that are still too vague
  - Missing verification steps
  - Tools that don't match sub-tasks

**Part 3: Boundaries & Escalation (12 minutes)**
- Critical for production systems
- Use the decision tree diagram to reinforce the concepts

**Part 4: Real-World Example (5 minutes)**
- Walk through the churn analysis Python pseudocode
- Highlight the "agent's thinking process"

### Microlesson 2: Multi-Agent Patterns (30 minutes)
**Part 1: Architecture Overview (8 minutes)**
- Use the Mermaid diagram to explain the pattern
- Emphasize cost efficiency as the key driver

**Part 2: Implementation & Benefits (12 minutes)**
- Code examples are for illustration—don't expect students to run them
- Focus on the conceptual patterns, not syntax details

**Part 3: Reproducibility & Wrap-up (5 minutes)**
- Critical for production deployment
- End with the module checklist to reinforce key concepts

## Teaching Tips

### For Interactive Exercises
- **Micro-Lab Timing:** Give exactly 8 minutes, then move on. Don't wait for everyone to finish.
- **Chat Review:** Select diverse examples that show different approaches.
- **Encourage Specificity:** Push students to be more specific in their decompositions.

### For Technical Content
- **Code Examples:** These are for illustration. Students should focus on the patterns, not implementation details.
- **Cost Analysis:** The specific pricing numbers may change; emphasize the relative differences.
- **Model Names:** Update model names if newer versions are available.

### For Discussions
- **Business Context:** Relate examples to students' actual work when possible.
- **Failure Stories:** Ask if anyone has experienced agent failures due to ambiguity.
- **Pattern Recognition:** Help students see how this applies beyond AI to general project management.

## Common Student Questions

**Q: "How granular should sub-tasks be?"**
A: Granular enough that each step has a clear success/failure condition, but not so granular that coordination overhead dominates. Start coarse, then refine based on failure patterns.

**Q: "What if the orchestrator fails?"**
A: Great question! This is why we need monitoring and fallback strategies. The orchestrator should be the most reliable component, using proven models and simple logic.

**Q: "How do you handle dependencies between sub-tasks?"**
A: Excellent advanced question. The orchestrator can manage dependencies by ordering tasks appropriately or using conditional logic. For complex dependencies, consider tools like LangGraph.

**Q: "Is this just microservices for AI?"**
A: Good analogy! Similar principles apply: single responsibility, clear interfaces, independent deployment. But AI agents have unique challenges like non-deterministic outputs and token costs.

## Timing Flexibility

**If Running Behind:**
- Skip the practice exercise discussion (just show one example)
- Reduce implementation code walkthrough time
- Focus on high-level patterns over details

**If Running Ahead:**
- Spend more time on student examples
- Dive deeper into cost analysis
- Discuss more failure scenarios and escalation strategies

## Assessment Opportunities

### Formative Assessment
- Monitor micro-lab progress and provide real-time feedback
- Use the module checklist as a quick knowledge check
- Observe student responses during interactive exercise

### Summative Assessment Ideas
- Have students decompose a complex business scenario
- Ask them to design escalation strategies for specific failure modes
- Request cost analysis for a multi-agent vs. single-agent approach

## Technical Prerequisites Check

Before starting, ensure students understand:
- Basic AI agent concepts (from Module 4.1)
- API calls and tool usage patterns
- Cost considerations in AI systems

If students lack these prerequisites, spend extra time on foundational concepts or provide additional resources.

## Troubleshooting

### If Students Struggle with Decomposition
- Start with simpler, more concrete examples
- Use analogies to project management or cooking recipes
- Provide a template with partially filled examples

### If Code Examples Cause Confusion
- Emphasize that code is illustrative only
- Focus on the logical flow, not syntax
- Use pseudocode or flowcharts instead

### If Timing Gets Off Track
- The interactive exercise and micro-lab are essential—don't skip these
- Other sections can be shortened if needed
- Always end with key takeaways, even if you don't cover everything

---

🏗️ **Under Construction**

We are constantly working to improve our resources for instructors and students.

**Have something to contribute to this Instructor Guide?** [Let us know](https://pages.git.generalassemb.ly/modular-curriculum-all-courses/universal-resources-internal/module-feedback.html).
