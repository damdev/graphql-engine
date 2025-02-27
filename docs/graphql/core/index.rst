.. meta::
   :description: Hasura GraphQL engine documentation
   :keywords: hasura, docs, manual, graphql engine

.. title:: Hasura GraphQL Engine Documentation

.. _core_docs:

Hasura GraphQL Engine Documentation
===================================

.. contents:: Table of contents
  :backlinks: none
  :depth: 1
  :local:

The Hasura GraphQL engine makes your data instantly accessible over a real-time GraphQL API, so you can build and
ship modern apps and APIs faster. Hasura connects to your databases, REST servers, GraphQL servers, and third party
APIs to provide a unified real-time GraphQL API across all your data sources.

.. container:: toc-list
  
  .. container:: toc-list-section

    .. container:: toc-list-head

      Basics

    .. container:: toc-list-content

      - :ref:`getting_started`
      - :ref:`pg_schema`
      - :ref:`pg_queries`
      - :ref:`pg_mutations`
      - :ref:`pg_subscriptions`

  .. container:: toc-list-section

    .. container:: toc-list-head

      Business Logic

    .. container:: toc-list-content

      - :ref:`actions`
      - :ref:`remote_schemas`
      - :ref:`event_triggers`
      - :ref:`scheduled_triggers`

  .. container:: toc-list-section

    .. container:: toc-list-head

      Auth

    .. container:: toc-list-content

      - :ref:`authentication`
      - :ref:`Auth Using Webhooks <auth_webhooks>`
      - :ref:`Auth Using JWT <auth_jwt>`
      - :ref:`Unauthenticated / Public Access <unauthenticated_access>`
      - :ref:`Authorization / Access Control <authorization>`

  .. container:: toc-list-section

    .. container:: toc-list-head

      CI/CD & Deployments

    .. container:: toc-list-content

      - :ref:`Migrations basics <migrations>`
      - :ref:`Setting Up Migrations <migrations_setup>`
      - :ref:`Managing Metadata <manage_hasura_metadata>`
      - :ref:`Server configuration <hge_flags>`
      - :ref:`Deploy Using Hasura Cloud <cloud_docs>`
      - :ref:`Deploy Using Docker <deployment_docker>`
      - :ref:`Deploy Using Kubernetes <deploy_kubernetes>`

  .. container:: toc-list-section

    .. container:: toc-list-head

      Reference

    .. container:: toc-list-content

      - :ref:`hasuracli_manual`
      - :ref:`api_reference`
      - :ref:`How It Works <how_it_works>`
      - :ref:`Troubleshooting <troubleshooting>`
      - :ref:`FAQs <faq>`
      - :ref:`security_protocol`

  .. container:: toc-list-section

    .. container:: toc-list-head

      Learn

    .. container:: toc-list-content

      - `30-Minute Hasura Basics Course <https://hasura.io/learn/graphql/hasura/introduction/>`__
      - `GraphQL & Hasura Courses <https://hasura.io/learn/>`__
      - :ref:`Guides & Resources <guides>`
      - :ref:`Updating to Hasura v2 <upgrade_hasura_v2>`


.. toctree::
  :maxdepth: 1
  :titlesonly:
  :hidden:

  getting-started/index
  databases/index
  actions/index
  remote-schemas/index
  event-triggers/index
  scheduled-triggers/index
  auth/index
  migrations/index
  Deploying <deployment/index>
  hasura-cli/index
  API Reference <api-reference/index>
  How It Works <how-it-works/index>
  Troubleshooting <troubleshooting/index>
  guides/index
  security-disclosure/index
