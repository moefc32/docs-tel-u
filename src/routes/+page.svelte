<svelte:head>
    <title>{import.meta.env.VITE_APP_NAME}</title>
    <meta property="og:title" content={import.meta.env.VITE_APP_NAME} />
</svelte:head>

<!-- svelte-ignore a11y_consider_explicit_label -->
<!-- svelte-ignore a11y_missing_attribute -->
<div class="flex flex-1 flex-col gap-3">
    <h1 class="my-3 pb-3 text-5xl border-b-[1px] border-gray-700">
        {import.meta.env.VITE_APP_NAME}
    </h1>
    <p>
        Simpledocs is a minimalistic and efficient documentation site designed
        for designers, developers, and teams who need a quick and organized way
        to present their documentation. It offers a clean and responsive layout
        with essential features like a navigation sidebar and search
        functionality. Built with simplicity in mind, this project ensures that
        users can focus on writing content without dealing with complex
        configurations. Its lightweight nature makes it easy to deploy on the
        GitHub Pages.
    </p>
</div>
