<template>
  <section class="maincontent">
    <div class="sidebar">
      <ul v-scroll-spy-active v-scroll-spy-link>
        <li>
          <a>Basics</a>
        </li>
        <li>
          <a>Engineer I</a>
        </li>
        <li>
          <a>Engineer II</a>
        </li>
        <li>
          <a>Senior Engineer</a>
        </li>
        <li>
          <a>Staff Engineer</a>
        </li>
        <li>
          <a>Principal Engineer</a>
        </li>
        <li>
          <a>Distinguished Engineer</a>
        </li>
        <li>
          <a>Misc: Project Lead</a>
        </li>
      </ul>
    </div>

    <div class="content" v-scroll-spy>
      <div>
        <h2>
          Basic Responsibilities
          <a href="#basics">#</a>
        </h2>
        <p class="italic">
          Everyone should work on these in every stage of their career.
        </p>
        <ul>
          <li>
            Actively participates in group discussions, groomings and problem
            solving with the team in general.
          </li>
          <li>
            Continually works to support teammates and is considerate of others'
            opinions, culture and beliefs.
          </li>
          <li>
            Communicates internally and externally in a respectful manner.
          </li>
        </ul>
      </div>
      <div>
        <h2 id="engineer-i">
          Engineer I
          <a href="#engineer-i">#</a>
        </h2>
        <ul>
          <li>
            Completes clearly-defined tasks and communicates when something is
            blocking.
          </li>
          <li>
            Works to learn the relevant technologies and systems in place,
            actively maintains and extends the system.
          </li>
          <li>
            Makes an impact by delivering features, refactoring existing code,
            or updating systems to enable other developers to be successful.
          </li>
          <li>
            Helps debug technical problems. Submits issues so that we can
            document and improve our digital products.
          </li>
        </ul>
        <p>
          <em><strong>Experience</strong>: No previous experience required.</em>
        </p>
      </div>
      <div>
        <h2 id="engineer-ii">
          Engineer II
          <a class="direct-link" href="#engineer-ii">#</a>
        </h2>
        <ul>
          <li>
            Works on engineering initiatives that drive a larger featureset,
            while being careful to not create technical debt in the process.
          </li>
          <li>
            Preemptively scans issue backlogs. Actions include but are not
            limited to: familiarizing themselves with pain points in the system,
            applying relevant labels and triaging, closing them via pull request
            or other means.
          </li>
          <li>
            Is considerate of others on the team and tries to support other
            people in their work.
          </li>
          <li>
            Works to become proficient in giving great reviews of their peers
            work. This includes being respectful, thorough, thoughtful,
            flexible, and not pedantic.
          </li>
          <li>
            Listens to the priorities and concerns of others, and acknowledges
            differing perspectives. Anticipates others’ reactions.
          </li>
        </ul>
        <p>
          <em>
            <strong>Experience</strong>: Typically requires a minimum of 2 years
            of professional experience.
          </em>
        </p>
      </div>
      <div>
        <h2 id="senior-engineer">
          Senior Engineer
          <a class="direct-link" href="#senior-engineer">#</a>
        </h2>
        <p class="italic">
          At this point, a person is mastering how effective they can be as an
          individual contributor.
        </p>
        <ul>
          <li>
            Helps support the work of their peers by pair programming,
            reviewing, and providing mentoring.
          </li>
          <li>
            Defines and executes on an execution plan for specific features or
            internal system maintenance/upgrade.
          </li>
          <li>Adjusts well to shifting priorities when necessary.</li>
          <li>
            Actively participates in Engineering efforts that help streamline
            the experience of our Product.
          </li>
          <li>
            Works to understand the purpose of the features the team is working
            on, and helps communicate that purpose to team members. Asks
            clarifying questions when expectations are unclear.
          </li>
          <li>
            Strives to reduce technical debt, while communicating with teammates
            about any larger refactor.
          </li>
          <li>
            When tasks are large, works on scoping work down into smaller,
            actionable parts.
          </li>
          <li>
            Demonstrates openness to others’ ideas. Adapts their communication
            style to most effectively communicate. Effectively and accurately
            shares credit for ideas and collaborative efforts.
          </li>
          <li>
            Structures code in a manner that anticipates the type of scale and
            maintenance required for the scope of the work. Considers legibility
            both in authoring and reviewing pull requests.
          </li>
          <li>
            At times, takes ownership of small to medium sized initiatives. This
            includes taking responsibility for timelines, and communication
            across teams when there are design or business related questions.
          </li>
        </ul>
        <p>
          <em>
            <strong>Experience</strong>: Typically requires a minimum of 5 years
            of professional experience.
          </em>
        </p>
      </div>
      <div>
        <h2 id="staff-engineer">
          Staff Engineer
          <a class="direct-link" href="#staff-engineer">#</a>
        </h2>
        <p class="italic">
          At this point, the majority of one's time is spent scaling their own
          skills to help others.
        </p>
        <ul>
          <li>
            Actively participates in meetings, and creates cross-team
            collaboration where necessary to address business goals.
          </li>
          <li>
            Creates and maintains internal documentation for the purpose and
            structure of the systems they're working on. Carefully documents
            processes that aren’t clear.
          </li>
          <li>
            Teaches peers how to set up systems and drive execution plans for
            features and system improvements.
          </li>
          <li>
            Coordinates efforts across the team rather than working in a silo.
            Makes sure that people feel included in varying projects, and that
            their voices are heard.
          </li>
          <li>
            Keeps the team moving quickly by working on engineering efforts that
            aren’t glamorous.
          </li>
          <li>
            Proactively communicates issues and addresses necessary trade-offs.
            Takes ownership of issues.
          </li>
          <li>
            Manages larger refactors, and/or system upgrades, helps others to do
            the same or participate. Able to estimate scope of work, and when
            those estimates are off, coordinates with stakeholders like Product
            Management to address risks, and take ownership.
          </li>
        </ul>
        <p>
          <em>
            <strong>Experience</strong>: Typically requires a minimum of 8 years
            of professional experience.
          </em>
        </p>
      </div>
      <div>
        <h2 id="principal-engineer">
          Principal Engineer
          <a class="direct-link" href="#principal-engineer">#</a>
        </h2>
        <p class="italic">
          At this point, one is helping others be the best that they can be,
          removing themselves and meeting others where they are.
        </p>
        <ul>
          <li>
            Develops proven systems. Replicates those systems and approaches
            across the team so that others may learn from and improve on them.
          </li>
          <li>
            Maintains deep industry knowledge and awareness of the technical
            landscape. Incorporates this analysis as appropriate into strategy.
          </li>
          <li>
            Not only leads, but ideates new engineering efforts. Provides
            guidance and vision.
          </li>
          <li>
            Mentors and actively drives the technical skills of the immediate or
            extended team with consideration of their career stage and personal
            trajectory.
          </li>
          <li>
            Removes barriers by working with others around a shared need or
            customer benefit.
          </li>
          <li>
            Creates strategies that cross organizational boundaries to achieve
            broad business goals or influence.
          </li>
          <li>
            Anticipates issues or implications that their ideas would have on
            others, and pursues mutually beneficial strategies.
          </li>
          <li>
            Beyond participating in meetings, thoughtfully creates and leads
            meetings where helpful.
          </li>
          <li>
            Sets clear and challenging goals for a portfolio of work, and
            pursues them with enthusiasm and passion.
          </li>
          <li>
            Understands business objectives and incorporates these into this
            body of work. Critically reviews multiple plans and adjusts as
            needed.
          </li>
          <li>
            Drives measurable growth by scaling/mentoring teams, affecting
            engineering roadmaps positively, managing key metrics, creating
            research and/or programs.
          </li>
          <li>
            Partners with other teams to improve the effectiveness of our
            internal tooling.
          </li>
          <li>
            Anticipates the needs of those around them. Is respectful in terms
            of async hygiene, exhibiting care that their teammates can get in
            touch with them or knows their status during working hours. Fills
            out process docs without having to be asked.
          </li>
        </ul>
        <p>
          <em>
            <strong>Experience</strong>: Typically requires a minimum of 10
            years of professional experience.
          </em>
        </p>
      </div>
      <div>
        <h2 id="distinguished-engineer">
          Distinguished Engineer
          <a class="direct-link" href="#distinguished-engineer">#</a>
        </h2>
        <ul>
          <li>
            Identifies industry-wide pieces of functionality that are missing
            that can unlock potential for customer growth at scale and
            implements them, either through engineering tasks, open source work,
            or advocating with product for features.
          </li>
          <li>
            Understands the impact their activity on company OKRs and chooses
            precisely what they’re working on in terms of strategy of that
            impact without being asked.
          </li>
          <li>
            Actively advocates for others internally and externally, making sure
            that their work is seen. Extends their social capital to aid other
            people.
          </li>
          <li>
            Works on system architecture, thinking through problems and
            anticipating usage into the future. Builds systems that scale
            appropriately.
          </li>
          <li>
            Carefully considers communication methods when collaborating,
            especially in tricky circumstances.
          </li>
          <li>
            Effectively communicates when there are problems, understanding
            risks and impact of any proposed changes. Listens well when others
            express tradeoffs next to other priorities.
          </li>
        </ul>
        <p>
          <em>
            <strong>Experience</strong>: Typically requires a minimum of 12
            years of professional experience.
          </em>
        </p>
      </div>
      <div>
        <h2 id="project-lead">
          Misc: Project Lead <a class="direct-link" href="#tech-lead">#</a>
        </h2>
        <p>
          A Project Lead is responsible for leading a particular project (large
          or small) and responsible for the quality of its technical
          deliverables.
        </p>
        <p class="italic">
          Anyone can lead a project at any stage in their career.
        </p>
        <ul>
          <li>
            Involves the concept of "owning a project" from the engineering
            side. Some responsibilities could include one or more of the
            following:
            <ul>
              <li>Identifying the technical approach.</li>
              <li>
                Creating task tickets to fill in gaps in acceptance criterea.
              </li>
              <li>Timeline management and completion estimates.</li>
              <li>
                Communication with stakeholders and managers around progress
                updates.
              </li>
            </ul>
          </li>
          <li>
            Helps organize and facilitate productive feedback sessions with
            stakeholders.
          </li>
          <li>
            Can include a good amount of project management, keeping the trains
            running on time, keeping folks unblocked, and raising concerns to
            management when folks are stuck or timelines aren't being met.
          </li>
          <li>
            Creates alignment with the overall project goals and how the
            execution is carried out. Brings up conflicts in a productive
            manner.
          </li>
          <li>
            Still involves coding/participation and IC work on a project. This
            might also mean picking up slack to fill in gaps to round out a
            project.
          </li>
        </ul>
      </div>
    </div>
  </section>
</template>
