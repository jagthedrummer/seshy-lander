---

title: Roles & Permissions
layout: markdown

---

<div class="border border-dashed rounded-lg border-yellow-500 bg-yellow-200 dark:bg-opacity-10 dark:border-yellow-200 dark:border-opacity-70 dark:text-white mb-8 p-3 xl:py-4 xl:px-4 xl:-mx-4">
  Note: This page is a work in progress and the roles described below are aspirational and don't fully exist or work as described yet.
  I'm documenting it ahead of time to gather feedback and to give people a chance to see what to expect soon.
</div>

## Roles & Permissions

Users who belong to a Team may have one or more Roles associated with
their membership on that Team.

These Roles help you manage who is allowed to do what
in terms of managing Projects, Teams, and Subscriptions.

The roles are explained in more detail below but this is the tl;dr:

* **Listener** (default) - can download projects, but not make updates
* **Project Collaborator** - can download and upload projects, can not delete or rename
* **Project Admin** - collaborator + can delete & rename (on projects owned by the team for which they have the project admin role), can also request/accept project transfers
* **Team Admin** - can invite other team members and update team settings
* **Billing Admin** - can update billing & extend subscription to other teams
* **Super Admin** - project admin + billing admin + team admin




### Project Roles & Permissions

* **Listner** - This is the default Role for any team member that doesn't have other Project related Roles specified.
  * ✅ can download projects
  * ❌ cannot update projects
  * ❌ cannot rename, delete or transfer projects

* **Project Collaborator**
  * ✅ can download projects
  * ✅ can update projects
  * ❌ cannot rename, delete or transfer projects

* **Project Admin** - This Role only applies to Projects that are owned by the same Team as the membership that grants this Role.
  * ✅ can download projects
  * ✅ can update projects
  * ✅ can rename, delete, &amp; transfer projects


### Team Roles & Permissions

* **Team Admin**
  * ✅ can invite new Team members
  * ✅ can change Team name &amp; settings

### Billing Roles & Permissions

* **Billing Admin**
  * ✅ can manage the Team Subscription
  * ✅ can extend a Team Subscription to addition Teams
  * ✅ can accept an extended Team Subscription from another Team

### Super Admin

This is a convenience Role that is assigned to you when you first create a team.
You can also use it to allow other users to have full control over a team.

* **Super Admin**
  * Project permissions
    * ✅ can download projects
    * ✅ can update projects
    * ✅ can rename, delete, &amp; transfer projects
  * Team permissions
    * ✅ can invite new Team members
    * ✅ can change Team name &amp; settings
  * Billing permission
    * ✅ can manage the Team Subscription
    * ✅ can extend a Team Subscription to addition Teams
    * ✅ can accept an extended Team Subscription from another Team

  


