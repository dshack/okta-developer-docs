---
title: Set up your Application
---

You set up your OpenID Connect application inside the Okta Admin Console:

1. From the side navigation, select **Applications** and then **Applications**.
1. On the Applications page, choose **Add Application**.
1. On the Create New Application page, select **Native** or **SPA**, depending on the type of application that you are working on.
  > **Note:** It is important to choose the appropriate application type for apps which are public clients. Failing to do so may result in Okta API endpoints attempting to verify an app's client secret, which public clients are not designed to have, hence breaking the sign-in or sign-out flow.
1. Fill-in the Application Settings, then click **Done**.

<NextSectionLink/>
