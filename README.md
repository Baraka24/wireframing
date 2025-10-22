# Wireframing

Wireframing is the practice of creating low-fidelity layouts that map the structure, hierarchy, and flow of a product or page. It focuses on placement, navigation, and key interactions—without final visuals, colors, or copy.

## What Is Wireframing?
- Visual blueprint of screens and states
- Emphasizes content priority, layout, and user flows
- Uses simple shapes and labels to represent components

## Why It Matters
- Aligns stakeholders on scope and expectations early
- Validates requirements and user journeys before costly design/build
- Accelerates iteration and reduces rework
- Improves communication across design, product, and engineering

## Where It Fits in the Design Process
- Early discovery and requirements gathering
- Information architecture and user flow exploration
- Prior to high-fidelity design, prototyping, and implementation
- As a reference during usability testing and refinement

## Key Elements of a Wireframe

### Layout Structure
- Defines grid, columns, spacing, and breakpoints; establishes visual hierarchy.
- Contributes by guiding attention and aligning components consistently.
- Example: A three-column grid with a fixed 240px sidebar keeps filters accessible on desktop; collapses to a drawer on mobile to preserve content space.

### Navigation
- Specifies global, local, and contextual navigation and their states.
- Contributes by clarifying paths, reducing backtracking, and surfacing key routes.
- Example: Top-level tabs for Dashboard, Reports, Settings; breadcrumbs within Reports; a sticky subnav exposing Overview, Trends, Export on long pages.

### Content Placement
- Positions headlines, primary/secondary content, and metadata using hierarchy.
- Contributes by prioritizing what users see first and supporting scanning (F/Z patterns).
- Example: KPI cards above the fold with clear labels; detailed table below; helper text adjacent to form fields to reduce errors.

### Functionality
- Maps interactions, controls, and states (hover, focus, disabled, loading, empty, error).
- Contributes by setting expectations for behavior and edge cases before visual design.
- Example: Inline edit in tables with validation; optimistic save with a toast; an empty state offering “Try a sample dataset” to unblock first-time users.

## Types of Wireframes

### Low-Fidelity Wireframes
- Simple sketches or basic digital layouts using boxes, lines, and placeholder text
- Focus on structure, layout, and flow without detail or polish
- Typically used during early ideation, brainstorming, and initial stakeholder alignment
- Fast to create and easy to iterate; encourage feedback on concepts rather than aesthetics
- Example tools: pen and paper, whiteboards, or simple diagramming software

### High-Fidelity Wireframes
- More detailed and refined, closer to final design with accurate spacing, typography hierarchy, and component representations
- May include realistic content, more precise interactions, and multiple states
- Typically used after validation of core concepts, during handoff preparation or usability testing
- Take longer to produce but provide clearer implementation guidance
- Example tools: Figma, Sketch, Adobe XD with component libraries and design systems

### This Document's Wireframe Type
The wireframes described in the **Key Elements** section above are **low-fidelity wireframes**. They use simple descriptions, abstract component references (e.g., "KPI cards," "sticky subnav"), and focus on placement and functionality rather than visual polish—making them ideal for early alignment and exploration.

## Popular Wireframing Tools

### Figma (Recommended)
Figma is a cloud-based design and prototyping tool that has become the industry standard for wireframing and collaborative design work.

**Key Features:**
- Real-time collaboration allowing multiple team members to work simultaneously
- Browser-based with no installation required; accessible from any device
- Robust component and design system support for consistency and reusability
- Built-in prototyping to demonstrate flows and interactions directly in wireframes
- Version history and branching for tracking iterations and changes
- Developer handoff features including CSS/code snippets and asset exports

**Why It's Useful for Wireframing:**
- Speed: Pre-built UI kits and auto-layout streamline low-fidelity creation
- Collaboration: Stakeholders can comment directly on frames, reducing feedback loops
- Scalability: Easily transition from low-fidelity sketches to high-fidelity designs in the same file
- Sharing: Simple link sharing for reviews without requiring software licenses
- Integration: Connects with tools like Jira, Slack, and FigJam for end-to-end workflow

### Other Tools
- **Sketch**: Mac-only vector design tool with strong plugin ecosystem; popular before Figma's rise
- **Adobe XD**: Adobe's design and prototyping platform with Creative Cloud integration
- **Balsamiq**: Deliberately low-fidelity tool with a hand-drawn aesthetic for rapid sketching
- **Miro/FigJam**: Collaborative whiteboarding platforms ideal for early ideation and team workshops
- **Axure RP**: Advanced prototyping tool with conditional logic for complex interaction modeling