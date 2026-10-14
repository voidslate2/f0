## XtremeLabs

https://corporate.xtremelabs.io/news/introducing-helix-instruct-instructor-kits/

We're excited to share something new with our MCT community!

We know how much time goes into preparing for a course, especially when you are teaching a new certification or trying to keep your materials up to date. Between creating slides, putting together exercises, and developing assessments, there is a lot of work that happens before class even begins.

That's why we've introduced Helix Instruct Instructor Kits, a collection of ready-to-use teaching resources designed to make course preparation easier.

What's Included in an Instructor Kit?
Each kit brings together the materials you need to prepare for and deliver a certification course, including:
Instructor Guides: Lesson plans, teaching notes, course objectives, and suggested pacing.
Presentation Slides: PowerPoint decks with speaker notes that you can use as-is or customize.
Assessments: Quizzes, practice questions, and other resources to check student understanding.
Labs & Activities: Hands-on exercises and classroom activities to reinforce key concepts.
Lab Module Maps: Guidance for aligning lab exercises with course topics.
Make the Materials Your Own
Every instructor teaches differently, and we don't expect you to change your approach to fit our materials.

Our Instructor Kits include editable resources, so you can adjust the content, add your own examples, and tailor the course to your students.

Whether you're preparing to teach a course for the first time or looking to update materials you've been using for years, these kits can help cut down on the time you spend getting everything ready.

Take a Look at Our New Instructor Kits
We're continuing to expand the collection and would love to hear which courses you'd like us to add next.

Explore Instructor Kits on the XtremeLabs Marketplace

You can also read more about Helix Instruct Instructor Kits and what's included.

Happy Training!

## DATABRICKS


Dear Databricks Customer,

We are reaching out to inform you about the upcoming End of Life (EOL) date for legacy foundation and embedding model serving endpoints. Your organization uses one or more of these endpoints that will stop serving requests on March 30, 2027. To avoid disruption, please migrate your workloads to Unity Gateway as soon as possible. Unity Gateway provides centralized governance across models, agents, MCPs, skills, and tools along with advanced capabilities like budgets, Smart Routing, and observability

What's Changing
On March 30, 2027, all Foundation and Embedding Model Serving Endpoints (Legacy) endpoints in your workspaces will no longer accept incoming requests. To avoid disruption to your production workloads, please redirect your workloads to call the new Unity Gateway as soon as possible.

New models will no longer be added to legacy endpoints starting Oct 15. They will be accessible and supported in Unity Gateway.

What is affected
This End of Life covers workspace-level foundation and embedding models serving endpoints for Pay-per-token Foundation models, Provisioned Throughput models, and external models.

What's not affected
All other serving endpoints, including Custom model and feature serving endpoints are not affected.

Required Action
To avoid disruption to your production workloads, please complete the following steps prior to March 30, 2027:

Identify impacted model serving endpoints using this notebook
Use our migration guide to move impacted endpoints to Unity Gateway
Update your applications to route traffic to the Unity Gateway model services endpoints.
Test and complete your migration prior to EOL date
We recommend that you begin this process early to allow time for configuration changes, testing, and any required internal approvals.

If you have questions, require assistance reviewing permissions, or need help planning your migration strategy, please reach out to your Databricks account team or contact help@databricks.com.

Thanks,
Databricks

This message was sent by Databricks Incident Management. For questions contact help@databricks.com.

## FABRIC SPARK 2.0

End of support notice: Upgrade Microsoft Fabric Runtime 1.3 to 2.0 by 31 March 2027
You’re receiving this notification because on or more of your Azure subscriptions associated with your Fabric capacity have been used with Microsoft Fabric Runtime 1.3.

Microsoft Fabric Runtime 1.3 will reach end of support on March 31, 2027. After this date, Runtime 1.3 will no longer be supported. We strongly recommend that you begin planning and validating your upgrade now and transition your workloads to Microsoft Fabric Runtime 2.0 as soon as possible, rather than waiting until the end-of-support date.

After end of support, Runtime 1.3 will be removed from Fabric workspace settings and Environment items. Any existing Spark job execution on Runtime 1.3 will start failing eventually after the deprecation date.

Moving to Runtime 2.0 also keeps your workloads on the latest GA runtime so you can benefit from ongoing platform innovations and improvements.

Recommended action

Complete these steps before 31 March 2027:

Review the Capacity ID and Capacity Name included with this notice and inventory the affected workspaces, environments, notebooks, and Spark job definitions.
Validate Runtime 2.0 with your workload in a non-production workspaces first and then transition to production workspaces.
In Workspace settings, go to Data Engineering/Science > Spark settings > Environment, select Runtime 2.0, and save. For an Environment item, select Runtime 2.0, save, and publish.
Update or replace incompatible libraries and JAR dependencies.
Validate notebooks, Spark jobs, libraries, data pipelines, and scheduled workloads before production rollout.
Don’t wait until the end-of-support deadline. We recommend starting validation and migration as soon as possible to allow sufficient time to identify and resolve application or dependency compatibility issues before March 31, 2027.

Help and support

If you have general questions, ask community experts in Microsoft Q&A. If you have a support plan and you need technical help, open the Azure portal and select the question mark icon at the top of the page. 

Account Information
Subscription ID: f5fd6e73-0d17-4620-a4c3-03f97451e559

Capacity ID: b9813390-d7d6-4ee0-b009-57fca258ddfd

Capacity Name: permfabric

   
This message from Microsoft is an important part of a program, service, or product that you or your company purchased or participates in. Microsoft respects your privacy. Please read our Privacy Statement .

This is a mandatory service communication. To set your contact preferences for other communications, visit the Promotional Communications Manager .

Microsoft Corporation, One Microsoft Way, Redmond, WA 98052


