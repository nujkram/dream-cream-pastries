<script>
	const data = [
		{
			id: '01',
			title: 'Lorem Ipsum',
			description:
				'Ulamco laboris nisi ut aliquip ex ea commodo consequat. Et consectetur ducimus vero placeat'
		},
		{
			id: '02',
			title: 'Repellat Nihil',
			description:
				'Dolorem est fugiat occaecati voluptate velit esse. Dicta veritatis dolor quod et vel dire leno para dest'
		},
        {
            id: '03',
            title: 'Ad ad velit qui',
            description:
                'Minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea '
        }
	];
</script>

<!-- ======= Why Us Section ======= -->
<section id="why-us" class="why-us">
	<div class="container" data-aos="fade-up">
		<div class="section-title">
			<h2>Why Us</h2>
			<p>Why Choose Our Restaurant</p>
		</div>

		<div class="row">
			{#each data as item}
                <div class="col-lg-4">
                    <div class="box" data-aos="zoom-in" data-aos-delay="100">
                        <span>{item.id}</span>
                        <h4>{item.title}</h4>
                        <p>
                           {item.description}
                        </p>
                    </div>
                </div>
            {/each}
		</div>
	</div>
</section>
<!-- End Why Us Section -->
