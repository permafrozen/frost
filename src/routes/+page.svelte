<script>
    import Title from "$lib/components/title.svelte";
    import Subtitle from "$lib/components/subtitle.svelte";
    import Content from "$lib/components/content.svelte";
    import H1 from "$lib/components/heading.svelte";
</script>

<div class="flex justify-center pt-20">
    <div class="flex flex-col justify-start items-center w-5/9">
        <div class="pb-25">
            <Title>HELLO WORLD</Title>
            <Subtitle>Salutations, dear Huzz</Subtitle>
        </div>

        <div class="px-40 *:pb-25">
            <div>
                <H1>About</H1>
                <Content>
                    Lorem ipsum dolor sit, amet consectetur adipisicing elit.
                    Maxime velit ab alias ut dolor tempora optio quia
                    consequuntur obcaecati consectetur, saepe itaque dolorum
                    placeat repellat dolorem exercitationem, deserunt quam
                    animi?
                </Content>
            </div>

            <div>
                <H1>Interests</H1>
                <Content>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Dolore aperiam placeat nobis excepturi qui facilis soluta
                    laborum pariatur dolorum magnam exercitationem, dolor
                    possimus. Suscipit culpa laboriosam cum, reiciendis
                    voluptates nam?
                </Content>
            </div>

            <div>
                <H1>Projects</H1>

                <Content>
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                    Obcaecati ullam aperiam, quaerat deserunt ducimus officia
                    repellendus doloribus nobis. Reprehenderit ut ipsa
                    consequatur illo beatae eaque non maiores magni eveniet
                    fuga?
                </Content>
            </div>
        </div>
    </div>
</div>
