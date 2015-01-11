Preface
---

Please read this proposal carefully.

  * It may contain elements that strongly resemble proposals made and rejected years ago.  Times have changed.  I ask everybody to evaluate this proposal anew, and not dwell on the past.

  * It may contain elements that strongly resemble proposals made within the past few weeks.  It may also be missing crucial elements from those proposals.  I ask that everybody evaluate this proposal as a standalone proposal.

Key elements of the proposal described below:

  * Participants will join the
    [W3C Web Applications Working Group](http://www.w3.org/2008/webapps/).
  * All technical work will be done by the
    [WHATWG](https://wiki.whatwg.org/wiki/FAQ#What_is_the_WHATWG.3F).
    The work will be informed by
    [implementation experience](http://www.w3.org/2014/Process-20140801/#implementation-experience).
  * The Web Applications Working Group will be primarily concerned with
    [transition requests](http://www.w3.org/2005/08/01-transitions.html#transreq).
  * This will result in updates to the
    [URL Technical Report](http://www.w3.org/TR/url/) published on the
    [W3C site](http://www.w3.org/TR/).

As an alternative to doing this work inside the WebApps WG, a new Working Group could be chartered.  A [draft charter](http://rawgit.com/webspecs/url/develop/docs/url-charter.html) is available for discussion.  If such
a charter were adopted, this workmode would need to be updated to change the name of the sponsoring Working Group.

This working group could even be a [joint WG with the IETF](http://xml2rfc.tools.ietf.org/cgi-bin/xml2rfc.cgi?url=https%3A%2F%2Fraw.githubusercontent.com%2Fwebspecs%2Furl%2Fdevelop%2Fdocs%2Furl-problem-statement.xml&modeAsFormat=html%2Fascii#rfc.section.5.1).

For reference purposes only, here are some related links:

  * [synchronization and consistency](http://lists.w3.org/Archives/Public/public-w3process/2014Dec/0004.html)
  * [Decision by consensus or by informed editor; which is better?](http://www.w3.org/blog/2014/10/decision-by-consensus-or-by-informed-editor-which-is-better/)
  * [Commit-Then-Review and snapshots](http://lists.w3.org/Archives/Public/public-w3process/2014Nov/0185.html)
  * [WHATWG/W3C Collaboration](http://intertwingly.net/blog/2014/11/20/WHATWG-W3C-Collaboration) - [no process change required](http://lists.w3.org/Archives/Public/public-w3process/2014Nov/0148.html)
  * [web specifications](http://lists.w3.org/Archives/Public/public-w3process/2014Nov/0177.html) - [draft](https://specs.webplatform.org/url/webspecs/develop/), [github](https://github.com/webspecs/url), [issues](https://github.com/webspecs/url/issues), [discourse](http://discourse.specifiction.org/c/url)
  * [attempt to engage the TAG and IETF](http://lists.w3.org/Archives/Public/public-whatwg-archive/2014Nov/0000.html) - [problem statement](http://intertwingly.net/projects/pegurl/url-problem-statement.html)

WorkMode
===

The [W3C Web Applications  Working Group](http://www.w3.org/2008/webapps/) has a published [WorkMode](http://www.w3.org/2008/webapps/wiki/WorkMode).  This is the WorkMode for the URL work during the 2015-2016 calendar years.  Extensions, early termination, and adoption of some or all of this by other efforts are all possible, but outside of the scope of this document.

Participation and Communication
---

The primary place for work on the URL standard has been, and continues to be:

  * [WHATWG mailing list](http://lists.w3.org/Archives/Public/public-whatwg-archive/) hosted by the W3C
  * [WHATWG/URL component in Bugzilla](https://www.w3.org/Bugs/Public/buglist.cgi?component=URL&list_id=48297&product=WHATWG&resolution=---) hosted by the W3C
  * [whatwg/url repository](https://github.com/whatwg/url) hosted by GitHub
  * [#whatwg IRC channel](https://wiki.whatwg.org/wiki/IRC) hosted by freenode

All technical communications are to take place on a publicly archived list.  As an example, this includes [www-archive](http://lists.w3.org/Archives/Public/www-archive/).  In general, the editors intend to aggressively follow up with any individual or group that has technical input and will bring the results of those efforts back to the venues mentioned above.  The current list of alternate venues being evaluated:

  * [webspecs/url repository](https://github.com/webspecs/url) hosted by GitHub
  * [public webapps mailing list](http://lists.w3.org/Archives/Public/public-webapps/) hosted by the W3C

The Technical Reports Process (What is an Editor's Draft?)
---

The [URL Living Standard](https://url.spec.whatwg.org/) is effectively an [Public Working Draft](http://www.w3.org/2014/Process-20140801/#revised-wd) and matches the description of an [Editor's draft](http://www.w3.org/2008/webapps/wiki/WorkMode#The_Technical_Reports_Process_.28What_is_an_Editor.27s_Draft.3F.29) as practiced by the WebApps WG.

There have been discussions concerning having a W3C Working Group such as
WebApps "sponsor" this effort; the proposal is that the WG would do so according to the workmode as
described by this page.  A decision to adopt this workmode be an entirely voluntary one by
the WebApps working group.

This would primarily involve the Working Group producing 
[Transition Requests](http://www.w3.org/2005/08/01-transitions.html#transreq).
As a part of doing so,  stable snapshots would be made.

The first such snapshot is available at
[http://www.w3.org/TR/2014/WD-url-1-20141209/](http://www.w3.org/TR/2014/WD-url-1-20141209/).
This snapshot is hosted by the W3C, using standard W3C stylesheets and
[logo](https://github.com/w3ctag/url/blob/develop/logo.include).  It is
[licensed](https://github.com/w3ctag/url/blob/develop/copyright.include) under the terms required by the
[WebApps charter](http://www.w3.org/2014/06/webapps-charter.html#deliverables).
It includes a [status](https://github.com/w3ctag/url/blob/develop/status.include) section.
It refers to the [WHATWG URL Standard](https://url.spec.whatwg.org/) as the
editor's draft.  The
[Acknowledgments](http://www.w3.org/TR/2014/WD-url-1-20141209/#acknowledgments)
section lists the editors, refers to the WHATWG standard as the upstream
draft, and mentions the license under which the WHATWG standard is made
available.

There are no technical content differences.  The content is pulled from the
[master branch of the whatwg GitHub repository](https://github.com/whatwg/url)
into the
[develop branch of the w3ctag GitHub repository](https://github.com/w3ctag/url/tree/develop).
The complete list of
[changes](https://github.com/w3ctag/url/compare/develop#diff-5) is available online.

Later in the process, the proposal is to adopt the
[Public Permissive version 3](http://dev.w3.org/html5/decision-policy/public-permissive-exit-criteria.html)
exit criteria in order to satisfy the need for demonstrating 
[Implementation Experience](http://www.w3.org/2014/Process-20140801/#implementation-experience).
Any changes needed to the specification to meet this exit criteria will be done in the 
[whatwg GitHub repository](https://github.com/whatwg/url), if necessary in a branch.

Also later in the process there may be possible differences in the normative references, primarily to meet the 
[W3C Normative References Policy](http://www.w3.org/2013/09/normative-references).  Those changes, if any, will be
done in the [w3ctag GitHub repository](https://github.com/w3ctag/url/tree/develop).

The WebApps Working Group would also need to record and present [Formal Objections](http://www.w3.org/2014/Process-20140801/#FormalObjection).  It is conceivable that the resolution of such a Formal Objection could result in a fork.  The process by which such a potential fork would be managed is outside of the scope of this document.

By the end of 1Q 2015, there will be a meeting with the W3C Director to review
all of this and determine if the WHATWG URL Living Standard can be referenced
directly instead.  The need for each of the changes listed above (logo, license,
status, references, acknowledgements) will be explored and challenged.

Editors
---

In the W3C, editors are [appointed by WG chairs](http://www.w3.org/2014/Process-20140801/#general-requirements).  In the WHATWG editors agree to add other editors.  Ideally, the way to make this work is for the W3C chairs of the WebApps working group voluntarily agree to limit their activities to confirming changes to editors, and for us to not spend time working out the implications of what would happen if such a change were not confirmed.

There is no predefined criteria for becoming an editor.  The most common way for this to occur is after a sustained period of producing quality pull requests.

Bugs, Issues and Actions
---

[Bugzilla](https://www.w3.org/Bugs/Public/buglist.cgi?component=URL&list_id=48297&product=WHATWG&resolution=---) and [github issues](https://github.com/webspecs/url/issues) are used by the URL Standard.

The WebApps working group may chose to track [actions items](http://www.w3.org/2008/webapps/track/).

Patent Policy
---

This is general agreement on [Royalty Free Licensing](http://www.w3.org/Consortium/Patent-Policy-20040205/#sec-Requirements) and [Disclosure](http://www.w3.org/Consortium/Patent-Policy-20040205/#sec-disclosure-requirements) requirements.  In practice, agreeing to join the relevant Working Group is a part of collecting the necessary commitments.  Unfortunately, there is a pervasive perception that the necessary agreements to do so impose requirements inconsistent with the working mode described on this page.  Specifically:

  * The [Invited Expert and Collaborator Agreement](http://www.w3.org/Consortium/Legal/2014/08-invited-expert.html) explicitly disallows «Branching», which would seem to preclude [GitHub pull requests](https://help.github.com/articles/using-pull-requests/).

  * Section 7 of
    [Appendix 1](http://www.w3.org/Consortium/Agreement/Appendix1-2013.html)
    of the [W3C Member Agreement](http://www.w3.org/2009/12/Member-Agreement)
    has been cited in the past as not permitting activities that seem similar to
    the workMode as described on this page.

An alternate approach that has been tried in the past is to use the CG process to obtain [licensing commitments](http://www.w3.org/community/whatwg/spec/82/commitments).

Also worth noting, the [acknowledgements](https://url.spec.whatwg.org/#acknowledgments) section contains a list of people who have already contributed.

For URL to become a W3C Recommendation, the W3C will need to define a workable
process that gets the necessary commitments without imposing unrelated
requirements.  The proposal is therefore to:

  * Get the W3C to publicly state that this WorkMode is consistent with the
    W3C Process, and therefore nothing in Section 7 of Appendix 1 of the
    Member agreement would inhibit this WorkMode being adopted.
  * Modify section 2.2 of the Invited Expert agreement to align it with the
    Member Agreement.  See also [issue 150](http://www.w3.org/community/w3process/track/issues/150)
    in the w3process CG.

Meetings
---

No telecons have been held or are expected.

Discussions on [#whatwg IRC channel](https://wiki.whatwg.org/wiki/IRC) are commonplace.

URL has been a topic of discussion at F2F meetings such as TPAC.  As is the custom with WebApps, any results are to be taken back to public mailing lists.

Consensus and Call for Consensus
---

The only Calls for Consensus by the WebApps working group relating to URL will
be for process related items: decisions to "sponsor" this work, decisions
related to exit criteria and transition requests, and decisions to host a fork
of this product.  Going into this agreement, everybody agrees that such a fork
is a measure of last resort.

Mail List Policy
---

Discussions that are held in various venues will conform to the norms expected of those venues.  No additional URL specific mailing list policies are being proposed or are expected.

Off-Topic Discussion Policy
---

Again, discussions that are held in various venues will conform to the norms expected of those venues.  As those venues generally are not limited in scope to the URL standard, messages on such lists may be unrelated to the URL standard.

IRC
---

Discussions related to the URL standard occur on [#whatwg IRC channel](https://wiki.whatwg.org/wiki/IRC).

Testing
---

Tests can be found in the [url/](https://github.com/w3c/web-platform-tests/tree/master/url) directory of [w3c/web-platform-tests](https://github.com/w3c/web-platform-tests).

Version Control
---

[whatwg/url](https://github.com/whatwg/url) and [webspecs/url](https://github.com/webspecs/url) repositories on GitHub are currently being actively used.  Neither consistently are "upstream" from each other, and the plans are to actively keep them in sync.

The [develop branch of the w3ctag GitHub
repository](https://github.com/w3ctag/url/tree/develop) will contain the
content from which drafts published on the W3C TR page are produced.

Links to Group Resources
---

A list of resources is available on [discourse.specifiction.org](http://discourse.specifiction.org/t/about-the-url-category/691).
