---

title: The conference team
layout: event_noheader
registration_url: /www-event-testtwo/register/
permalink: about/team/

---


<section class="team-list">
	<h2>Organizing Committee</h2>
	<ul >
	{% for member in site.data.team.conferenceteam %}
	<li>
		<div style="background-image: url(/www-event-testtwo/assets/images/team/{{member.image | default: 'owasp_logo.png'}})" alt="{{member.name}} {{member.role}}"></div>
		<h4>{{member.name}}</h4>
		<span class="role">{{member.role}}</span>
	</li>
	{% endfor %}
	</ul>
</section>
<section class="team-list">
	<h2>OWASP Staff</h2>
	<ul>
	{% for member in site.data.team.staff %}
	<li>
		<div style="background-image: url(/www-event-testtwo/assets/images/team/{{member.image | default: 'owasp_logo.png'}})" alt="{{member.name}} {{member.role}}"></div>
		<h4>{{member.name}}</h4>
		<span class="role">{{member.role}}</span>
	</li>
	{% endfor %}
	</ul>
</section>

