<template>
  <b-container>
    <b-row>
      <b-col cols="8" offset="2">
        <h1>Mazda CX-3 Questions</h1>
        <b-button variant="link info" class="p-0">Ask a question</b-button>
      </b-col>
      <b-col cols="8" offset="2">
        <b-button variant="info">2016 Mazda CX-3</b-button>
        <b-button variant="info">2017 Mazda CX-3</b-button>
        <b-button variant="info">Safety</b-button>

        <vh-button variation="secondary">
          Test
        </vh-button>

        <VhChip>
          <VhIcon name="checkCircle" color="darkBlue" slot="icon-left" />

          2018 Mazda CX-3
        </VhChip>

        <!-- <button
          type="button"
          data-gtm-trigger="click"
          data-gtm-value="[consumer-reviews] Comfort Subject Filter Chip"
          class="VhChip ConsumerReviewKeywords-keywordChip VhChip--hover VhChip--medium"
          data-v-becde372=""
        >
          <span class="VhChip-iconLeft"></span>
          <span class="VhChip-content">
            2018 Mazda CX-3
          </span>
        </button> -->
      </b-col>
      <b-col cols="8" offset="2">
        <h2>I'm looking at the 2016 model, does it have a backup camera?</h2>
        <b-badge variant="info">2016 Mazda CX-3</b-badge>
        <b-badge variant="info">Safety</b-badge>
        <b-col cols="2">
          <Vote />
        </b-col>
        <b-col cols="10">
          <p>
            Great gas mileage, safety features such as back-up camera and blind
            spot detectors on side mirrors, CX-3 model is a bit small - back
            seat passengers do not have a lot of space for their legs or
            anything else that might be transported in the back, radio system
            started having trouble connecting to Bluetooth on my phone after
            about a year.
          </p>
        </b-col>
      </b-col>
      <b-col cols="8" offset="2">
        <b-button variant="primary">Submit your question</b-button>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
import Vote from '~/components/Vote.vue'
import { VhButton, VhChip, VhIcon } from '@vehiclehistory/ui/dist/sfc'

export default {
  components: {
    Vote,
    VhButton,
    VhChip,
    VhIcon
  }
}
</script>
