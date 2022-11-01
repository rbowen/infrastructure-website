
layout: post
title: Email service interruption and restoration July 12, 2022
date: '2022-07-13T16:41:38+00:00'
permalink: email-service-interruption-and-restoration

<p><b>July 13, 2022</b></p><p><span style="color: rgb(23, 43, 77); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Roboto, Oxygen, Ubuntu, &quot;Fira Sans&quot;, &quot;Droid Sans&quot;, &quot;Helvetica Neue&quot;, sans-serif;">At around 09:11 UTC on Tuesday, July 12th 2022, the primary mailing list server (colloquially known as <b>Hermes</b>) at The Apache Software Foundation suffered a fatal breakdown and became unresponsive.</span><br></p><p style="margin-bottom: 0px; padding: 0px; color: rgb(23, 43, 77); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Roboto, Oxygen, Ubuntu, &quot;Fira Sans&quot;, &quot;Droid Sans&quot;, &quot;Helvetica Neue&quot;, sans-serif;">The Infrastructure team (Infra) was immediately notified and, in cooperation with our data center provider, attempted to restore services and notify the Foundation of the outage.</p><p style="margin-bottom: 0px; padding: 0px; color: rgb(23, 43, 77); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Roboto, Oxygen, Ubuntu, &quot;Fira Sans&quot;, &quot;Droid Sans&quot;, &quot;Helvetica Neue&quot;, sans-serif;">As restoring the machine to a useful state proved more difficult than we had hoped, and due to the importance of this service to the Foundation, Infra decided to "fail forward" at approximately 14:40 UTC, and migrate all affected mailing lists and accounts to the new replacement mailing list server for the Foundation (<b>mailgw</b>). We had announced the start of this migration on June 15, 2022.</p><p class="auto-cursor-target" style="margin-bottom: 0px; padding: 0px; color: rgb(23, 43, 77); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Roboto, Oxygen, Ubuntu, &quot;Fira Sans&quot;, &quot;Droid Sans&quot;, &quot;Helvetica Neue&quot;, sans-serif;">At approximately 17:33 UTC the bulk of our migration operations had completed, and mail was flowing again. The team continued to address and monitor issues arising as a result of the migration, and the mailing list services were deemed fully operational at approximately 20:00 UTC.</p>