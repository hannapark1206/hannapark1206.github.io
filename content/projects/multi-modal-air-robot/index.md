<style>
.article-metadata,
.toc-sidebar,
.page-toc,
.docs-toc,
#TableOfContents {
  display: none !important;
}

/* remove default article width limits */
.article-container,
.docs-article-container,
.page-body,
.prose,
.max-w-prose,
.universal-wrapper,
.container {
  max-width: none !important;
}

/* exactly about 1 inch margin on each side */
.portfolio-page-wrap {
  width: calc(100vw - 2in) !important;
  max-width: none !important;
  margin-left: 50% !important;
  transform: translateX(-50%) !important;
}

/* let the hero/video/text use the full page width */
.portfolio-hero {
  margin-top: 1rem;
  margin-bottom: 2.3rem;
  max-width: none !important;
  width: 100% !important;
}

.project-video-wrap {
  width: 100%;
  margin-bottom: 1.6rem;
}

.project-video {
  width: 100%;
  max-height: 560px;
  object-fit: cover;
  border-radius: 22px;
  border: 1px solid #e5e7eb;
  box-shadow: 0 10px 28px rgba(0,0,0,0.08);
  background: #000;
}

.project-kicker {
  font-size: 0.9rem;
  font-weight: 700;
  letter-spacing: 0.04em;
  text-transform: uppercase;
  color: #4f46e5;
  margin-bottom: 0.8rem;
}

.project-lede {
  font-size: 1.18rem;
  line-height: 1.65;
  color: #374151;
  max-width: none !important;
  width: 100% !important;
}

.skill-row {
  display: flex;
  flex-wrap: wrap;
  gap: 0.55rem;
  margin-top: 1rem;
  margin-bottom: 1.5rem;
}

.skill-chip {
  display: inline-flex;
  align-items: center;
  border: 1px solid #dbe3ff;
  background: #f5f7ff;
  color: #27324a;
  border-radius: 12px;
  padding: 0.42rem 0.75rem;
  font-size: 0.88rem;
  font-weight: 600;
  line-height: 1.2;
}

.two-col {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 1.4rem;
  margin-top: 1rem;
  margin-bottom: 2rem;
}

.two-col > div {
  border: 1px solid #e5e7eb;
  border-radius: 18px;
  padding: 1.2rem 1.3rem;
  background: #ffffff;
  box-shadow: 0 8px 24px rgba(0,0,0,0.04);
}

@media (max-width: 850px) {
  .portfolio-page-wrap {
    width: calc(100vw - 2rem) !important;
  }

  .two-col {
    grid-template-columns: 1fr;
  }
}
</style>
