---
type: PageLayout
title: Yarina Laufer - Avocat
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: 'Yarina Laufer, AVOCAT'
    subtitle: >-
      Yarina Laufer este un avocat de renume, specializat în dreptul afacerilor,
      achiziții publice și soluționarea disputelor comerciale. De-a lungul
      carierei sale, a oferit consultanță strategică unor companii de top,
      asigurând conformitatea juridică și protejând interesele clienților săi în
      fața provocărilor legislative și comerciale.Expertiză și competențeYarina
      are o abordare pragmatică și orientată spre soluții, punând accent
      pe:Achiziții publice și contracte comerciale – oferind asistență juridică
      în proceduri de achiziții publice, inclusiv în fața autorităților
      contractante și instanțelor de contencios administrativ;Dreptul societar
      și fuziuni & achiziții – consiliind companii în tranzacții complexe,
      restructurări și conformitate legislativă;Litigii și arbitraj –
      reprezentând clienți în litigii comerciale, administrative și în fața
      instanțelor naționale și internaționale;Dreptul proprietății intelectuale
      – protejând și gestionând portofolii de mărci și drepturi de autor în
      diverse industrii.O carieră construită pe excelențăCu un parcurs
      profesional impresionant, Yarina a colaborat cu firme de avocatură de
      prestigiu și a gestionat cazuri complexe cu impact semnificativ în mediul
      de afaceri. Implicarea sa în proiecte internaționale, precum și
      colaborarea strânsă cu autoritățile de reglementare, o recomandă drept un
      expert de încredere.Abordare personalizată și strategie inovatoarePrin
      înțelegerea profundă a contextului economic și juridic, Yarina oferă
      soluții inovatoare adaptate fiecărui client. Rigoarea profesională și
      pasiunea pentru drept fac din ea un partener valoros pentru orice companie
      care dorește să navigheze cu succes prin complexitatea legislației
      moderne.Pentru consultanță juridică specializată, contactează Yarina
      Laufer și beneficiază de expertiza sa în domeniul juridic și afaceri.
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: flex-start
        justifyContent: flex-start
        flexDirection: row-reverse
        borderWidth: 5
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions: []
    text: >+
      Pentru consultanță juridică specializată, contactează Yarina Laufer și
      beneficiază de expertiza sa în domeniul juridic și afaceri.



  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See all projects
        url: /projects
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    subtitle: Projects
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-f
    variant: variant-d
    subtitle: Featured Posts
    showFeaturedImage: false
    actions:
      - type: Link
        label: See all posts
        url: /blog
    posts:
      - content/pages/blog/post-six.md
      - content/pages/blog/post-four.md
      - content/pages/blog/post-three.md
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-28
          - pb-48
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: "Got an interesting project? Tell me more...\U0001F4AC"
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: 1/2
          type: EmailFormControl
        - name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: updatesConsent
          label: Sign me up to recieve updates
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---
