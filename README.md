[index.html](https://github.com/user-attachments/files/26647930/privacy-policy.html)
<!doctype html>
<html lang="en">
<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>GhostMap Privacy Policy</title>
    <meta
        name="description"
        content="Privacy Policy for GhostMap, a paid Android app distributed through Google Play." />
    <style>
        :root {
            color-scheme: dark;
            --bg: #0b0f14;
            --panel: #121922;
            --panel-2: #18212b;
            --text: #eef4fb;
            --muted: #aab7c7;
            --accent: #8fd9ff;
            --line: #283445;
        }

        * {
            box-sizing: border-box;
        }

        html,
        body {
            margin: 0;
            padding: 0;
            background:
                radial-gradient(circle at top, rgba(255, 255, 255, 0.05), transparent 42%),
                linear-gradient(180deg, #0d1218 0%, var(--bg) 100%);
            color: var(--text);
            font-family: "Segoe UI", Roboto, Arial, sans-serif;
            line-height: 1.65;
        }

        body {
            padding: 32px 18px 64px;
        }

        .wrap {
            max-width: 920px;
            margin: 0 auto;
        }

        .hero,
        .section {
            background: linear-gradient(180deg, rgba(255, 255, 255, 0.03), rgba(255, 255, 255, 0.015));
            border: 1px solid var(--line);
            border-radius: 20px;
            padding: 24px;
            backdrop-filter: blur(8px);
        }

        .hero {
            margin-bottom: 18px;
        }

        .section {
            margin-bottom: 14px;
        }

        h1,
        h2,
        h3 {
            margin: 0 0 12px;
            line-height: 1.2;
        }

        h1 {
            font-size: clamp(2rem, 3.8vw, 3rem);
            letter-spacing: -0.03em;
        }

        h2 {
            font-size: 1.2rem;
            color: var(--accent);
        }

        h3 {
            font-size: 1rem;
            color: #d8e7f8;
        }

        p,
        li {
            color: var(--muted);
            margin: 0 0 10px;
        }

        ul {
            margin: 10px 0 0 20px;
            padding: 0;
        }

        .meta {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin: 14px 0 0;
        }

        .chip {
            display: inline-flex;
            align-items: center;
            min-height: 34px;
            padding: 0 12px;
            border: 1px solid var(--line);
            border-radius: 999px;
            background: var(--panel-2);
            color: #d7e8fa;
            font-size: 0.92rem;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
            gap: 12px;
            margin-top: 14px;
        }

        .card {
            background: var(--panel);
            border: 1px solid var(--line);
            border-radius: 16px;
            padding: 16px;
        }

        .note {
            border-left: 3px solid var(--accent);
            padding-left: 12px;
        }

        .placeholder {
            color: #ffe08f;
            font-weight: 600;
        }

        a {
            color: var(--accent);
        }

        code {
            font-family: Consolas, "Courier New", monospace;
            background: rgba(255, 255, 255, 0.06);
            padding: 1px 6px;
            border-radius: 6px;
            color: #f2f7fd;
        }
    </style>
</head>
<body>
    <div class="wrap">
        <section class="hero">
            <h1>GhostMap Privacy Policy</h1>
            <p>
                This Privacy Policy explains what data GhostMap accesses, how that data is used,
                how long it is retained, and what choices users have.
            </p>
            <div class="meta">
                <span class="chip">Last updated: April 12, 2026</span>
                <span class="chip">App: GhostMap</span>
                <span class="chip">Distribution: Google Play</span>
                <span class="chip">Business model: Paid app</span>
            </div>
        </section>

        <section class="section">
            <h2>1. Developer Information</h2>
            <p>
                This Privacy Policy applies to GhostMap published by
                <span class="placeholder">BEAT</span>.
            </p>
            <div class="grid">
                <div class="card">
                    <h3>Developer</h3>
                    <p><span class="placeholder">BEAT</span></p>
                </div>
                <div class="card">
                    <h3>Support Email</h3>
                    <p><span class="placeholder">kieukute2k4@gmail.com</span></p>
                </div>
                <div class="card">
                    <h3>Region</h3>
                    <p><span class="placeholder">VIETNAM</span></p>
                </div>
            </div>
        </section>

        <section class="section">
            <h2>2. Summary</h2>
            <p>GhostMap is designed to process most data locally on the user’s device.</p>
            <ul>
                <li>GhostMap does not create user accounts.</li>
                <li>GhostMap does not sell user data.</li>
                <li>GhostMap does not use advertising SDKs.</li>
                <li>GhostMap does not transmit user data to the developer’s own remote servers in the current version of the app.</li>
            </ul>
            <p class="note">
                GhostMap does access certain device and app data locally in order to provide overlay,
                key mapping, profile management, virtual mouse, and input-related features.
            </p>
        </section>

        <section class="section">
            <h2>3. Data the App Accesses and Uses</h2>

            <h3>3.1 Installed apps information</h3>
            <p>
                GhostMap reads the list of launchable apps installed on the device so the user can
                view apps, assign profiles to specific games or apps, and launch selected targets from within GhostMap.
            </p>
            <p>
                This may include app package names, app labels, and launcher icons.
            </p>

            <h3>3.2 Input-related data</h3>
            <p>
                When the user enables relevant features, GhostMap may access low-level keyboard, mouse,
                or controller input data on the device in order to:
            </p>
            <ul>
                <li>trigger user-configured mappings</li>
                <li>provide virtual mouse behavior</li>
                <li>provide key mapping behavior</li>
                <li>support overlay runtime features</li>
                <li>inject local touch/input events through Shizuku-enabled system APIs</li>
            </ul>
            <p>This processing is performed locally on the device.</p>

            <h3>3.3 Overlay and runtime state</h3>
            <p>
                GhostMap uses overlay windows and runtime state to display floating controls,
                editor windows, runtime controls, profile UI, and related mapping interfaces.
            </p>

            <h3>3.4 User-created configuration data</h3>
            <p>GhostMap stores user-created and user-selected app data locally, including for example:</p>
            <ul>
                <li>mapping profiles</li>
                <li>profile names</li>
                <li>selected target package names</li>
                <li>button bindings</li>
                <li>layout positions</li>
                <li>editor settings</li>
                <li>theme and language preferences</li>
                <li>active profile selections</li>
            </ul>

            <h3>3.5 Import and export files chosen by the user</h3>
            <p>
                If the user imports or exports profiles, GhostMap accesses only files explicitly chosen
                by the user for import, or files created by GhostMap for export at the user’s request.
            </p>
        </section>

        <section class="section">
            <h2>4. How the Data Is Used</h2>
            <p>GhostMap uses accessed data only to provide app features requested by the user, including:</p>
            <ul>
                <li>listing installed apps so profiles can be linked to games or apps</li>
                <li>storing and loading profile and mapping configurations</li>
                <li>reading local input events to execute configured mappings</li>
                <li>injecting local input or touch events when enabled by the user</li>
                <li>rendering overlays, runtime controls, and editor interfaces</li>
                <li>importing and exporting profile files</li>
                <li>remembering app UI preferences such as theme and language</li>
            </ul>
        </section>

        <section class="section">
            <h2>5. Data Sharing</h2>
            <p>GhostMap does not sell or rent personal data.</p>
            <p>GhostMap does not share personal data with third parties for advertising or marketing.</p>
            <p>In the current version of the app, GhostMap does not send user data to the developer’s own remote servers.</p>
            <p>
                GhostMap does interact locally with Android system services, the Shizuku service on the
                user’s device, and Google Play systems for app distribution and purchase processing.
                These interactions are required for the app to function as intended.
            </p>
        </section>

        <section class="section">
            <h2>6. Payments and Billing</h2>
            <p>GhostMap is a paid app distributed through Google Play.</p>
            <p>
                Any app purchase, payment processing, billing, refund handling, or transaction processing
                is handled by Google Play, not directly by GhostMap.
            </p>
            <p>GhostMap does not collect, store, or process:</p>
            <ul>
                <li>payment card numbers</li>
                <li>bank account details</li>
                <li>full payment credentials</li>
            </ul>
            <p>
                Google may process transaction-related data according to Google’s own policies and terms.
                Users should review Google Play’s and Google’s privacy terms for payment-related processing.
            </p>
        </section>

        <section class="section">
            <h2>7. Data Storage, Retention, and Deletion</h2>

            <h3>7.1 Local storage</h3>
            <p>GhostMap stores its app data locally on the user’s device.</p>

            <h3>7.2 Retention</h3>
            <p>Data is retained:</p>
            <ul>
                <li>until the user deletes profiles or settings inside the app</li>
                <li>until the user clears app data</li>
                <li>until the user uninstalls the app</li>
            </ul>
            <p>
                Exported profile files may remain in the export location until the user deletes them manually.
            </p>

            <h3>7.3 Deletion</h3>
            <p>Users can delete data by:</p>
            <ul>
                <li>deleting profiles or settings in the app</li>
                <li>clearing app data through Android settings</li>
                <li>uninstalling the app</li>
                <li>deleting exported files manually from device storage</li>
            </ul>
        </section>

        <section class="section">
            <h2>8. Security</h2>
            <p>
                GhostMap is designed to minimize unnecessary data transfer by processing data locally where possible.
            </p>
            <p>
                Because GhostMap includes overlay and input-related functionality, users should only grant
                permissions they understand and intend to use, including Shizuku-related access and overlay-related access.
            </p>
            <p>
                No system can be guaranteed to be absolutely secure, but GhostMap is designed to limit data
                exposure by avoiding unnecessary remote transmission in the current version.
            </p>
        </section>

        <section class="section">
            <h2>9. Children</h2>
            <p>GhostMap is not directed to children.</p>
        </section>

        <section class="section">
            <h2>10. User Choices</h2>
            <p>Users may choose whether to:</p>
            <ul>
                <li>install or purchase the app through Google Play</li>
                <li>grant overlay-related permissions</li>
                <li>grant Shizuku-related access</li>
                <li>enable or disable app features that rely on low-level input handling</li>
                <li>import or export profile files</li>
                <li>delete local profiles and settings</li>
            </ul>
        </section>

        <section class="section">
            <h2>11. Changes to This Privacy Policy</h2>
            <p>
                This Privacy Policy may be updated from time to time. If the policy changes, the latest version
                will be made available through the public Privacy Policy URL associated with the app listing or
                otherwise made available to users.
            </p>
        </section>

        <section class="section">
            <h2>12. Contact</h2>
            <p>
                If you have questions about this Privacy Policy, contact:
            </p>
            <p>
                <strong class="placeholder">BEAT</strong><br />
                <span class="placeholder">kieukute2k4@gmail.com</span>
            </p>
        </section>
    </div>
</body>
</html>
